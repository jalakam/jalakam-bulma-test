---
layout: post
title: Introduction to Linux
date: 2018-05-15 21:30:39
img_url: true
img: http://res.cloudinary.com/chipprogrammer/image/upload/c_limit,q_auto:low,w_668/v1526404917/blog/image_w8zcid.png
category: Linux
color: pink
theme_color: "#e91e63"
tags: Linux
---

A new operating system kernel was introduced by a Finnish student named **Linus Torvalds** in 1991 as a part of his personal project. This operating system kernal was named **Linux** and it was a free operating system kernel. 
> The Linus Torvalds had want to name his invention **Freax**(It was a linguistical blend of words "freak", "free", and "X" as an allusion to Unix). So he stored the program files under the name "Freax". Torvalds had already considered the name "Linux". But he think that it is too egotistical. In order to facilitate development, the files were uploaded to the FTP server of FUNET in September 1991. Ari Lemmke at Helsinki University of Technology (HUT), who was one of the volunteer administrators for the FTP server at the time, did not think that "Freax" was a good name. So, he named the project "Linux" on the server without consulting Torvalds. Later, however, Torvalds consented to "**Linux**".

## What is Unix?

The UNIX operating system was originally developed at **Bell Laboratories**, once part of the
telecommunications giant **AT&T**. Designed in the 1970s for Digital Equipment PDP computers, it has
become a very popular multiuser, multitasking operating system for a wide variety of different hardware
platforms, from PC workstations right up to multiprocessor servers and supercomputers.

Strictly, UNIX is a trademark administered by X/Open and refers to a computer operating system that
conforms to the X/Open specification XPG4.2. This specification, also known as SPEC1170, defines the
names of, interfaces to and behaviors of all UNIX operating system functions. The X/Open specification is
largely a superset of an earlier series of specifications, the P1003, or POSIX specifications, actively being
developed by the IEEE (Institute of Electrical and Electronic Engineers).

Many UNIX−like systems are available, either commercially, such as Sun's Solaris for SPARC and Intel
processors, or for free, such as FreeBSD and Linux. Only a few systems currently conform to the X/Open
specification, which allows them to be branded UNIX98. In the past, compatibility between different UNIX
systems has been a problem, although POSIX was a great help in this respect. With the publication of the
X/Open specification, there's hope that UNIX and the many other UNIX−like systems will converge.

### Unix: Milestones

|  Year  |           Event happen                                          |
|:------:|-----------------------------------------------------------------|
|  1957  | Unix operating system project began at Bell laborataries.       |
|  1957  | Bell laborataries created BESYS operating system to sequence their jobs.|
|  1964  | Researchers from General Electric, MIT, and Bell Labs created a new general-purpose, multi-user, time-sharing operating system called Multiplexed Information and Computing System(Multics).
|  1969  | Multics project was withdrawn because of the high cost of development |
|  1969  |  Ken Thompson, Dennis  Ritchie, Douglas Ritchie, and Douglas Mcllroy, along with a few others, began working on Uniplexed Information and Computing System (UNICS) by using an old PDP-7 computer |
|  1969  | The name Unics was then shortened to Unix. |
|  1969  | While working on the early assembly versions of Unix, Thompson worked on a FORTRAN compiler that evolved to support the language B, which was a smaller version of BCPL. |
|  1971  | First edition of Unix appeared along with the B compiler. |
|  1972  | Second edition of Unix was released. |
|  1973  | Third edition of Unix appeared along with the Unix C compiler (cc). |
|  1973  | Fourth edition of Unix was released. The kernel was rewritten in the C compiler. |
|  1974  | Fifth edition of Unix was released. The source code was made freely available to universities for educational purposes. Unix also spread outside AT&T and Bell Labs and was provided to academic institutions at a very small charge. |
|  1974  | Thompson taught Unix for a year at the University of California, Berkeley. |
|  1974  | When Thompson returned to Bell Labs, students and professors at Berkeley continued to enhance Unix. This led to the formation of the Berkeley Software Distribution, BSD. |
|  1975  | Sixth edition of Unix was released(V6 Unix) |
|  1975  | 1BSD, the fi rst edition, was released |
|  1978  | 2BSD, the second edition, was released |
|  1979  | Seventh edition of Unix was released. This edition was released along with Steve Bourne’s shell (sh). |
|  1979  | The development of Unix split into two main branches: System 5-SYS V(developed by AT&T and other commercial companies) and Berkeley software distribution-BSD(developed by students and professors University of California, Berkley). |
|  1979  |  3BSD, the third edition, was released |
|  1980  | 4.0BSD, the fourth version of the BSD Unix variant, was released |
|  1982  | AT&T transferred its Unix development to Western Electric, the System III version of Unix. |
|  1983  | Western Electric released System V, whereas System IV was reserved for only AT&T’s use |
|  1984  | The USG<sup>*</sup> group, which was renamed the UNIX system development laboratory (USDL) group, released System V Release 2 (SVR2), which was the fi rst version of Unix that supported paging, shared memory, and other associated features. |
|  1985  | Eighth edition of Unix was released on the basis of the 4.1BSD version. |
|  1987  | The USDL group, which was renamed AT&T Information Systems (ATTIS) group, released System V Release 3 (SVR3) |
|  1988  | 9<sup>th</sup> version of Unix was developed, and it was based on the 4.3BSD version. |
|  1989  | 10<sup>th</sup> version of Unix was developed. |
{: class="w3-responsive"}

{% include MyNote.html note_type="info" span_note="Why C language is named so?" text="<br />It was named &#8220;C&#8221; because its features were derived from an earlier language called &#8220;B &#8221;, which according to Ken Thompson was a stripped-down version of the BCPL programming language which was using B compiler. C came out of Dennis Ritchie's Unix project at AT&T." %}

## What is Linux?
Linux is a freely distributed implementation of a **UNIX−like kernel**, the low level
core of an operating system. Because Linux takes the UNIX system as its inspiration, Linux and UNIX programs are very similar. In fact, almost all programs written for UNIX can be compiled and run under Linux. Also, many commercial applications sold for commercial versions of UNIX can run unchanged in binary form on Linux systems. Linux was developed by Linus Torvalds at the University of Helsinki, with the help of UNIX programmers from across the Internet. It began as a hobby inspired by Andy Tanenbaum's Minix, a small UNIX system, but has grown to become a complete UNIX system in its own right. The Linux kernel doesn't use code from AT&T or any other proprietary source.
