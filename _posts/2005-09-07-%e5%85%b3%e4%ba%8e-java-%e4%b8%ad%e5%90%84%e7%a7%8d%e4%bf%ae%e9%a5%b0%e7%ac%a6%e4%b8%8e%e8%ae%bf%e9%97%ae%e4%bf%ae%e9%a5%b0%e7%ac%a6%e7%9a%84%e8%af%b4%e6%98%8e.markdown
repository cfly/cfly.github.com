---
layout: post
status: publish
published: true
title: 关于 Java 中各种修饰符与访问修饰符的说明
author_url: http://caofei.org
wordpress_id: 59
wordpress_url: http://caofei.wordpress.com/2005/09/07/%e5%85%b3%e4%ba%8e-java-%e4%b8%ad%e5%90%84%e7%a7%8d%e4%bf%ae%e9%a5%b0%e7%ac%a6%e4%b8%8e%e8%ae%bf%e9%97%ae%e4%bf%ae%e9%a5%b0%e7%ac%a6%e7%9a%84%e8%af%b4%e6%98%8e
date: '2005-09-07 00:55:12 +0800'
date_gmt: '2005-09-06 16:55:12 +0800'
categories:
- 计算机与 Internet
tags: []
comments: []
---
<div id="msgcns!66CD003054696B87!395" class="bvMsg">
<div>
<h1 style="text-align:center;" align="center">关于 Java 中各种修饰符与访问修饰符的说明 </h1>
<h2>类： </h2>
<div><i>访问修饰符   </i><i>修饰符   </i><b>class </b><b>类名称 </b><i>extends </i><i>父类名称 implement </i><i>接口名称 </i></div>
<div>（访问修饰符与修饰符的位置可以互换） </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>访问修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div>public </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div>可以被所有类访问（使用） </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>public 类必须定义在和类名相同的同名文件中 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div>package </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div>可以被同一个包中的类访问（使用） </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>默认的访问权限，可以省略此关键字，可以定义在和 public 类的同一个文件中 </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div>final </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div>使用此修饰符的类不能够被继承 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div>abstract </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div>如果要使用 abstract 类，之前必须首先建一个继承 abstract 类的新类，新类中实现 abstract 类中的抽象方法。 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>类只要有一个 abstract 方法，类就必须定义为 abstract ，但 abstract 类不一定非要保护 abstract 方法不可 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:59.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="79">
<div>  </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:171pt;border-bottom:windowtext .5pt solid;" valign="top" width="228">
<div>  </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<h2>变量 </h2>
<div style="text-indent:-21pt;">l          Java 中没有全局变量，只有方法变量、实例变量（类中的非静态变量）、类变量（类中的静态变量）。 </div>
<div style="text-indent:-21pt;">l          方法中的变量不能够有访问修饰符。所以下面<b>访问修饰符表</b>仅针对于在类中定义的变量。 </div>
<div style="text-indent:-21pt;">l          声明实例变量时，如果没有赋初值，将被初始化为 null （引用类型）或者 0 、 false （原始类型）。 </div>
<div style="text-indent:-21pt;">l          可以通过实例变量初始化器来初始化较复杂的实例变量，实例变量初始化器是一个用 &#123;&#125; 包含的语句块，在类的构造器被调用时运行，运行于父类构造器之后，构造器之前。 </div>
<div style="text-indent:-21pt;">l          类变量（静态变量）也可以通过类变量初始化器来进行初始化，类变量初始化器是一个用 static&#123;&#125; 包含的语句块，只可能被初始化一次。 </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>访问修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>public </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以被任何类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>protected </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以被同一包中的所有类访问 </div>
<div>可以被所有子类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>子类没有在同一包中也可以访问 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>private </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>只能够被当前类的方法访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>缺省 </div>
<div>无访问修饰符 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以被同一包中的所有类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>如果子类没有在同一个包中，也不能访问 </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>static </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>静态变量（又称为类变量，其它的称为实例变量） </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>可以被类的所有实例共享。 </div>
<div>并不需要创建类的实例就可以访问静态变量 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>final </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>常量，值只能够分配一次，不能更改 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>注意不要使用 const ，虽然它和 C 、 C++ 中的 const 关键字含义一样 </div>
<div>可以同 static 一起使用，避免对类的每个实例维护一个拷贝 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>transient </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>告诉编译器，在类对象序列化的时候，此变量不需要持久保存 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>主要是因为改变量可以通过其它变量来得到，使用它是为了性能的问题 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>volatile </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>指出可能有多个线程修改此变量，要求编译器优化以保证对此变量的修改能够被正确的处理 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<h2>方法 </h2>
<div><i>访问修饰符 </i><i>修饰符 </i><i>返回类型 </i><b>方法名称（ </b><i>参数列表 </i><b>） </b><i>throws </i><i>违例列表 </i></div>
<div style="text-indent:-21pt;">l          类的构造器方法不能够有修饰符、返回类型和 throws 子句 </div>
<div style="text-indent:-21pt;">l          类的构造器方法被调用时，它首先调用父类的构造器方法，然后运行实例变量和静态变量的初始化器，然后才运行构造器本身。 </div>
<div style="text-indent:-21pt;">l          如果构造器方法没有显示的调用一个父类的构造器，那么编译器会自动为它加上一个默认的 super() ，而如果父类又没有默认的无参数构造器，编译器就会报错。 super 必须是构造器方法的第一个子句。 </div>
<div style="text-indent:-21pt;">l          注意理解 private 构造器方法的使用技巧。 </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>访问修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>public </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以从所有类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>protected </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以被同一包中的所有类访问 </div>
<div>可以被所有子类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>子类没有在同一包中也可以访问 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>private </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>只能够被当前类的方法访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>缺省 </div>
<div>无访问修饰符 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>可以被同一包中的所有类访问 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>如果子类没有在同一个包中，也不能访问 </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>static </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>静态方法（又称为类方法，其它的称为实例方法） </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>提供不依赖于类实例的服务 </div>
<div>并不需要创建类的实例就可以访问静态方法 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>final </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>防止任何子类重载该方法 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>注意不要使用 const ，虽然它和 C 、 C++ 中的 const 关键字含义一样 </div>
<div>可以同 static 一起使用，避免对类的每个实例维护一个拷贝 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>abstract </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>抽象方法，类中已声明而没有实现的方法 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>不能将 static 方法、 final 方法或者类的构造器方法声明为 abstract </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>native </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>用该修饰符定义的方法在类中没有实现，而大多数情况下该方法的实现是用 C 、 C++ 编写的。 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>参见 Sun 的 Java Native 接口（ JNI ）， JNI 提供了运行时加载一个 native 方法的实现，并将其于一个 Java 类关联的功能 </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>synchronized </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>多线程的支持 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>当一个此方法被调用时，没有其它线程能够调用该方法，其它的 synchronized 方法也不能调用该方法，直到该方法返回 </div>
</td>
</tr>
</tbody>
</table>
<div>  </div>
<h2>接口 </h2>
<div><i>访问修饰符 </i><b>interface </b><b>接口名称 </b><i>extends </i><i>接口列表 </i></div>
<div style="text-indent:-21pt;">l          接口不能够定义其声明的方法的任何实现 </div>
<div style="text-indent:-21pt;">l          接口中的变量总是需要定义为“ public static final 接口名称”，但可以不包含这些修饰符，编译器默认就是这样，显示的包含修饰符主要是为了程序清晰 </div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:windowtext .5pt solid;border-left:windowtext .5pt solid;width:426.1pt;border-bottom:windowtext .5pt solid;" valign="top" width="568" colspan="3">
<div><b>访问修饰符 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div><b>名称 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div><b>说明 </b></div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div><b>备注 </b></div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>public </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>所有 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
<tr>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:windowtext .5pt solid;width:77.4pt;border-bottom:windowtext .5pt solid;" valign="top" width="103">
<div>无访问修饰符（默认） </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:153pt;border-bottom:windowtext .5pt solid;" valign="top" width="204">
<div>同一个包内 </div>
</td>
<td style="border-right:windowtext .5pt solid;border-top:medium none;border-left:medium none;width:195.7pt;border-bottom:windowtext .5pt solid;" valign="top" width="261">
<div>  </div>
</td>
</tr>
</tbody>
</table>
<div><i>  </i></div>
</div>
</div>
