---
layout: post
title:  "use cocoapods"
date:   2015-02-23 02:09:46
categories:
---
前一阵想做个IOS app，看了一些相关教程，觉得应该有好多开源库可以直接用。
大概查了一下，有个[cocoapods]做依赖库管理的东西。
大概类似于[maven]的pom，或者[ruby]的Gemfile。

建立一个Xcode工程，然后pod setup 会报错，如下

```
cflys-mba:sample cfly$ pod setup
Setting up CocoaPods master repo
[!] There was an error reading '/Users/cfly/.cocoapods/repos/master/CocoaPods-version.yml'.
Please consult http://blog.cocoapods.org/Repairing-Our-Broken-Specs-Repository/ for more information.
```
按照链接看过去。照着解决办法

```
cflys-mba:sample cfly$ rm -fr ~/.cocoapods/repos/master
cflys-mba:sample cfly$ pod setup
Setting up CocoaPods master repo
[!] There was an error reading '/Users/cfly/.cocoapods/repos/master/CocoaPods-version.yml'.
Please consult http://blog.cocoapods.org/Repairing-Our-Broken-Specs-Repository/ for more information.
```
问题依旧。想起来前一阵折腾jekyll时因为psych升级导致不兼容，马上`gem list psych`

```
psych (2.0.13, 2.0.8)
```
接着`gem uninstall psych`，再`gem list psych`，

```
psych (2.0.8)
```
只留下2.0.8试试

```
cflys-mba:podsample cfly$ pod setup
Setting up CocoaPods master repo
Updating a5da3b1..58580b2

Fast-forward

 Specs/DTKeychain/1.0.1/DTKeychain.podspec.json | 32 ++++++++++++++++++++++++++

 Specs/UTIKit/1.0.0/UTIKit.podspec.json         | 25 ++++++++++++++++++++

 2 files changed, 57 insertions(+)

 create mode 100644 Specs/DTKeychain/1.0.1/DTKeychain.podspec.json

 create mode 100644 Specs/UTIKit/1.0.0/UTIKit.podspec.json
From https://github.com/CocoaPods/Specs

   a5da3b1..58580b2  master     -> origin/master

CocoaPods 0.36.0.beta.2 is available.
To update use: `sudo gem install cocoapods --pre`
[!] This is a test version we'd love you to try.

For more information see http://blog.cocoapods.org
and the CHANGELOG for this version http://git.io/BaH8pQ.

Setup completed
```
OK，然后加入依赖库，[AFNetworking]。
Podfile中加入

```
platform :ios, '7.0'
pod "AFNetworking", "~> 2.0"
```
走起`pod install`

```
cflys-mba:podsample cfly$ pod install
Analyzing dependencies

CocoaPods 0.36.0.beta.2 is available.
To update use: `sudo gem install cocoapods --pre`
[!] This is a test version we'd love you to try.

For more information see http://blog.cocoapods.org
and the CHANGELOG for this version http://git.io/BaH8pQ.

Downloading dependencies
Installing AFNetworking (2.5.1)
Generating Pods project
Integrating client project

[!] From now on use `podsample.xcworkspace`.
```
然后打开podsample.xcworkspace再看，pods的库里已经有[AFNetworking]了。

看了一下都是objective-c的，我想用新出的swift做个东西，看来还是要了解objective-c，短时间内躲不开。
[cocoapods]:http://cocoapods.org
[maven]:http://maven.apache.org
[ruby]:http://www.ruby-lang.org/ 
[AFNetworking]:	http://afnetworking.com/