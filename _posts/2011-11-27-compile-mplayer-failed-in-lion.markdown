---
layout: post
status: publish
published: true
title: compile mplayer failed in lion
author_url: http://caofei.org
wordpress_id: 102
wordpress_url: http://caofei.wordpress.com/?p=102
date: '2011-11-27 16:41:57 +0800'
date_gmt: '2011-11-27 08:41:57 +0800'
categories:
- Computers and Internet
- 娱乐
tags: []
comments: []
---
<p>听说mplayer加了硬解，想弄一个看1080p，下了源码之后编译不过，xcode的llvm-gcc不给力，查了一下说是编译器不对，于是装了gcc45。依然不过，查了一下有人说用gcc42,如下<br />
export CC=/usr/bin/gcc-4.2<br />
，然后./configure &amp;&amp; make &amp;&amp; sudo make install</p>
<p>然后ok。</p>
<p>MPlayer SVN-r34363-4.2.1 (C) 2000-2011 MPlayer Team<br />
Usage:   mplayer [options] [url|path/]filename</p>
<p>Basic options: (complete list in the man page)<br />
-vo &lt;drv&gt;        select video output driver ('-vo help' for a list)<br />
-ao &lt;drv&gt;        select audio output driver ('-ao help' for a list)<br />
vcd://&lt;trackno&gt;  play (S)VCD (Super Video CD) track (raw device, no mount)<br />
dvd://&lt;titleno&gt;  play DVD title from device instead of plain file<br />
-alang/-slang    select DVD audio/subtitle language (by 2-char country code)<br />
-ss &lt;position&gt;   seek to given (seconds or hh:mm:ss) position<br />
-nosound         do not play sound<br />
-fs              fullscreen playback (or -vm, -zoom, details in the man page)<br />
-x &lt;x&gt; -y &lt;y&gt;    set display resolution (for use with -vm or -zoom)<br />
-sub &lt;file&gt;      specify subtitle file to use (also see -subfps, -subdelay)<br />
-playlist &lt;file&gt; specify playlist file<br />
-vid x -aid y    select video (x) and audio (y) stream to play<br />
-fps x -srate y  change video (x fps) and audio (y Hz) rate<br />
-pp &lt;quality&gt;    enable postprocessing filter (details in the man page)<br />
-framedrop       enable frame dropping (for slow machines)</p>
<p>Basic keys: (complete list in the man page, also check input.conf)<br />
&lt;-  or  -&gt;       seek backward/forward 10 seconds<br />
down or up       seek backward/forward  1 minute<br />
pgdown or pgup   seek backward/forward 10 minutes<br />
&lt; or &gt;           step backward/forward in playlist<br />
p or SPACE       pause movie (press any key to continue)<br />
q or ESC         stop playing and quit program<br />
+ or -           adjust audio delay by +/- 0.1 second<br />
o                cycle OSD mode:  none / seekbar / seekbar + timer<br />
* or /           increase or decrease PCM volume<br />
x or z           adjust subtitle delay by +/- 0.1 second<br />
r or t           adjust subtitle position up/down, also see -vf expand</p>
<p>* * * SEE THE MAN PAGE FOR DETAILS, FURTHER (ADVANCED) OPTIONS AND KEYS * * *</p>
<p>不过在我的macbook pro下依然声音跟不上，cpu100%。装了个<a href="http://xbmc.org/">xbmc</a>。能看了，不过风扇狂转。</p>
