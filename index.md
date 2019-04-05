---
layout: default
title: Home
---
# Introduction

<p class="lead">
Computer networks and operating systems deliver essential services for the
Internet-enabled applications of the modern world.  Whether it's video
streaming applications on your laptop, messaging apps on your smartphone or web
servers in huge data centres, all rely on the services of an operating system
and a computer network.
</p>

<img src="assets/images/kv5002.png" alt="KV5002 image" class="img-responsive center-block"/>

The security of your data has never been more important
nor more threatened than it is today. This module will help you to understand
the main ideas of networks and operating systems, and how to use their services
to develop secure networked applications. You will be taught in well-equipped
computing laboratories with modern operating systems and networks that you can
investigate and experiment with. Your understanding of key concepts and your
practical skills will be assessed by a single coursework assignment in which
you will develop a networked application and demonstrate your critical
understanding in a short report. This module will help you to develop a sound
understanding of key concepts for the age of the Internet and will inform your
thinking at every stage of your computing career.


# Module Team

|   |    |
|---|:---|
|Module Tutor &nbsp;  | [David Kendall](http://computing.northumbria.ac.uk/staff/cgdk2)|
|Lecturer      | [Alun Moon](http://computing.northumbria.ac.uk/staff/cgam1)|
|Lecturer      | [Kezhi Wang](https://sites.google.com/site/drkezhiwang/)|
|Lecturer      | [Bo Wei](https://weibo053001.bitbucket.io/)|
|TA      | [Ranjith Dinakaran](mailto:ranjith.dinakaran@northumbria.ac.uk)



# Teaching Arrangements

|   |    |
|---|:---|
**Lecture** &nbsp;    | Mon 15.00 - 16.00 WJN 002 (DK/AM)
**Lecture**           | Tue 10.00 - 11.00 WJN 002 (DK/AM)
**Lab/Seminar**       | Wed 09.00 - 11.00 CIS 202 (AM, KW)
**Lab/Seminar**       | Wed 11.00 - 13.00 CIS 201 (AM, KW)
**Lab/Seminar**       | Fri 11.00 - 13.00 CIS 201 (KW, BW)

<p class="text-info">
You should attend <em>both</em> lecture sessions and <em>one</em> of the
lab/seminar sessions every week. Refer to your personal timetable to identify
the lab session that you should attend.
</p>

# Synopsis

This module introduces you to the fundamentals of computer networks, security
and operating systems, including: network architecture and the five-layer
Internet protocol stack, processes/threads, inter-process communication, memory
management, file systems, and operating systems and network security. You will
study:

* network architecture: the five-layer Internet protocol stack (application,
  transport, network, datalink, and physical layers), switching techniques
  (e.g. circuit and packet), protocols (e.g. TCP, UDP, IP);

* processes and threads: concepts, use and implementation, creation and
  destruction, context switching, scheduling, synchronisation;

* inter-process communication: shared memory, message passing, pipes, sockets; 

* memory management: memory allocation schemes, paging, virtual memory;

* file systems: file concept, file system structure and implementation,
  directories, free space allocation;

* operating system and network security: confidentiality, integrity,
  availability, threats and attacks (e.g. denial of service, spoofing,
  man-in-the-middle), access control, user authentication, cryptography for
  data and network security, secure network protocols (e.g. TLS/SSL).

# Teaching Plan

The following is a *provisional* guide to the organisation of
this part of the module for this year. These arrangements are subject to
change during the course of the module.


| Week   | W/c   | Lecture 1   | Lecture 2   | Practical   |
| :----: | :---: | :---------: | :---------: | :---------: |
**1** | 28-Jan &nbsp; | [Introduction and Overview]({{site.baseurl}}{{site.raurl}}/01-1.pdf) (DK) <br/> Reading: [A-D15 Chp. 1](http://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf) &nbsp; | [Introduction to Unix/Linux. Linux Command Line]({{site.baseurl}}{{site.raurl}}/01-2.pdf) (DK) &nbsp; <br/> Reading: [SHO16, Chp. 1-6, 9]({{site.baseurl}}{{site.raurl}}/TLCL.pdf)| [Introduction to Lab Environment and Tools](L01.html) (DK)
**2** | 04-Feb &nbsp; | [C Programming]({{site.baseurl}}{{site.raurl}}/02-1.pdf) (AM) &nbsp; | [C Programming]({{site.baseurl}}{{site.raurl}}/02-2.pdf) (AM) &nbsp; | [Exercises in C Programming](L02.html) (AM)
**3** | 11-Feb &nbsp; | [Process Concept and Process scheduling]({{site.baseurl}}{{site.raurl}}/03-1.pdf) (AM) &nbsp; <br/> Reading: [A-D15 Chp. 7](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)| [Linux Processes]({{site.baseurl}}{{site.raurl}}/03-2.pdf) &nbsp; (DK) <br/> Reading: [A-D15 Chp. 5](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf)| [Working with Processes](L03.html) (DK)
**4** | 18-Feb &nbsp; | [Memory Management&nbsp;1]({{site.baseurl}}{{site.raurl}}/04-1.pdf) (AM) &nbsp; <br/> Reading: [A-D15 Chp. 13](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)| [POSIX Threads: create, exit, join, self]({{site.baseurl}}{{site.raurl}}/04-2.pdf) (DK) &nbsp; <br/> Reading: [AD-15 Chp. 27.1-27.2](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf) | [Using the POSIX Threads API: create, exit, join, self](L04.html) (DK)
**5** | 25-Feb &nbsp; | [Interference, Race Conditions, Mutual Exclusion]({{site.baseurl}}{{site.raurl}}/05-1.pdf) (DK) &nbsp; <br/> Reading: [A-D15 Chp. 26](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf) | [POSIX Semaphores]({{site.baseurl}}{{site.raurl}}/05-2.pdf) (DK) &nbsp; <br/> Reading: [A-D15 Chp. 31](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf)  | [Using Semaphores](L05.html) (DK)
**6** | 04-Mar &nbsp; | [Storage Management&nbsp;1]({{site.baseurl}}{{site.raurl}}/06-1.pdf) (AM) &nbsp; <br/> Reading: [AD-15 Chp. 39](http://pages.cs.wisc.edu/~remzi/OSTEP/file-intro.pdf)| [Storage Management&nbsp;2]({{site.baseurl}}{{site.raurl}}/06-2.pdf) (AM) &nbsp; <br/> Reading: [AD-15 Chp. 40](http://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf) | [Working with Files](L06.html) (AM) <br/> Introduction to the assignment
**7** | 11-Mar &nbsp; | [Transport Layer]({{site.baseurl}}{{site.raurl}}/07-1.pdf) (DK) | [Socket API: TCP]({{site.baseurl}}{{site.raurl}}/07-2.pdf) (AM) &nbsp; |  [TCP: Client/Server](L07.html) (AM) 
**8** | 18-Mar &nbsp; | [Transport Layer (ctd.)]({{site.baseurl}}{{site.raurl}}/08-1.pdf) (DK) | [Socket API: UDP]({{site.baseurl}}{{site.raurl}}/08-2.pdf) (AM) &nbsp; | [Communicating with UDP](L08.html) (AM)
**9** | 25-Mar &nbsp; | [Network Layer: Data plane]({{site.baseurl}}{{site.raurl}}/09-1.pdf) (DK) | [Network Layer: Control plane]({{site.baseurl}}{{site.raurl}}/09-2.pdf) (DK) | [Network Layer exercises](L09.html) (DK)
**10** | 01-Apr &nbsp; | [Application Layer]({{site.baseurl}}{{site.raurl}}/10-1) (AM) &nbsp; | [Physical and Link Layers]({{site.baseurl}}{{site.raurl}}/10-2.pdf) (AM) &nbsp; | [Networking Lab](L10.html) (AM)
**11** | 29-Apr &nbsp; | [Security]({{site.baseurl}}{{site.raurl}}/11-1.pdf) (DK) &nbsp; | [Security]({{site.baseurl}}{{site.raurl}}/11-2.pdf) (DK) &nbsp; | Assignment support
**12** | 06-May &nbsp; | Bank Holiday - No lecture &nbsp; | [Security]({{site.baseurl}}{{site.raurl}}/12-2.pdf) (DK) &nbsp; | Assignment support

<br/>

<p class="text-info">
In addition to the taught sessions, you are expected to undertake
independent and directed learning. This is a 20-credit module, for
which the expected student workload is 200 hours. Over the course of a
15-week semester, you should be spending about 13 hours per week on
this module.
</p>

# Assessment
Summative assessment comprises a single coursework assignment. You will be required to develop a networked application program and to write a short report (~1000-1500 words), demonstrating your critical understanding of the work done and of fundamental principles and concepts, using your own research of the academic and technical literature where appropriate.

Allocation of marks for the assignment will be as follows:
    • Program functionality and code quality: 30%
    • Critical understanding of program as demonstrated in report: 20%
    • Understanding of principles and concepts demonstrated in report: 50%

The assignment is entirely individual work and assesses all module learning
outcomes:

Knowledge & Understanding: 

1. Demonstrate knowledge and critical understanding of networking fundamentals,
   including network architecture and protocols.

2. Demonstrate knowledge and critical understanding of the fundamentals of an
   operating system, including its architecture and the implementation of its
   services.

3. Demonstrate knowledge and critical understanding of operating systems and
   network security, including fundamental concepts, threats, attacks and basic
   techniques for defence.

Intellectual / Professional skills & abilities:

4. Interpret a requirements specification to design and develop a networked
   application program, using standard operating systems and networking APIs
   (e.g. POSIX.1-2008), and demonstrating cognisance of security issues and
   industry best practice.

Personal Values Attributes (Global / Cultural awareness, Ethics, Curiosity) (PVA):

5. Communicate the results of work/study reliably and accurately.

<a class="btn btn-large btn-primary" href="{{site.baseurl}}{{site.raurl}}/assgn.pdf"><i class="icon-upload-alt"></i>Download Assignment Specification</a>


Formative assessment comprises a variety of theoretical and practical
exercises with opportunities for discussion with tutors and
colleagues.

Feedback on formative assessment will be given during the seminar and
laboratory sessions. Formal written feedback will be provided on the
assignment. 

# Recommended Reading

There is no essential textbook for this module. [SGG13] is an excellent
introduction to operating systems in general and can be used to supplement the
slides for the lectures. [A-D15] also covers much of this
material and has the advantage of being available *free online*.  The other
recommended books and papers give useful information on parts of the syllabus
only.


* **Books**
  - **[SGG13]** Silberschatz, A., Galvin, P., and Gagne,
G., [Operating System Concepts](https://www.amazon.co.uk/Operating-System-Concepts-Abraham-Silberschatz/dp/1118093755/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1505287999&amp;sr=1-1&amp;keywords=silberschatz+operating), John Wiley &amp; Sons, 9th edition, 2013, ISBN-13: 978-1118093757

  - **[KR16]** Kurose, J., and Ross, K., [Computer Networking: A Top-Down Approach](https://www.amazon.co.uk/Computer-Networking-Top-Down-Approach-Global/dp/1292153598/ref=sr_1_1?ie=UTF8&qid=1546938483&sr=8-1&keywords=kurose+ross), Pearson, 2016, ISBN-13: 978-1292153599

  - **[A-D15]** Arpaci-Dusseau, R. and Arpaci-Dusseau, A., [Operating systems: Three easy pieces](http://www.ostep.org), Arpaci-Dusseau Books, 2015

  - **[DOW08]** Downey, A., [The Little Book of
Semaphores](http://www.greenteapress.com/semaphores/) ([Local copy]({{site.baseurl}}{{site.raurl}}/downey08semaphores.pdf)), Green Tea Press, 2002 <br/> A free text book by Allen Downey that introduces a variety of interesting synchronisation
problems and their solution using semaphores.

  - **[SHO16]** Shotts. W., [The Linux Command Line](http://linuxcommand.org/tlcl.php) ([Local copy]({{site.baseurl}}{{site.raurl}}/TLCL.pdf)), No Starch Press, 2016 <br/> A free text book by William Shotts on using the Linux command line.

# Resources

* **Programming in C**
  - **[KOC04]** Kochan, S., [Programming in C](http://www.amazon.co.uk/Programming-Developers-Library-Stephen-Kochan/dp/0672326663/ref=sr_1_5?ie=UTF8&amp;qid=1316089219&amp;sr=8-5), Sams, 2004 <br/>
A gentle introduction to programming in C. I think it's a better starting
point than the much-recommended Kernighan and Ritchie.
  - **[PRI02]** Prinz, P., [C Pocket Reference](http://www.amazon.co.uk/C-Pocket-Reference-Peter-Prinz/dp/0596004362/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1285570456&amp;sr=1-1), O'Reilly, 2002 <br/>
A concise C reference. Very cheap. Less than a fiver the last time I
looked. I suggest you buy a copy and read it from cover to cover.
  - **[BBD91]**  Banahan, M., Brady, D.  and Doran, M., [The C Book](http://publications.gbdirect.co.uk/c_book/), Currently out of print, 1991. <br/>
Although this book is no longer in print, it remains a good introduction to the C language.
There's a [free pdf version](http://publications.gbdirect.co.uk/c_book/thecbook.pdf)
available ([local copy]({{site.baseurl}}{{site.raurl}}/thecbook.pdf)).
  - [Essential C](http://cslibrary.stanford.edu/101/EssentialC.pdf), Parlante, N, Stanford University, 2003 <br/>
A very good summary of the basic features of the C language.
  - [Learn C Programming](http://tutorialspoint.com/cprogramming/) <br/> A nice online C programming tutorial site.
  - [C Programming](http://kom.aau.dk/~jdn/edu/doc/c/tutorials/c-course-strathclyde/) <br/>
An online course on C Programming from the University of Strathclyde.
  - [Practical Programming in C](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-087-practical-programming-in-c-january-iap-2010/index.htm) <br/> A detailed introduction to C from the MIT Open Courseware catalogue. If you skip the material on data structures and concurrency, you're left
with a good basic introduction to C. The data structures and concurrency
sections cover more advanced material.
* **Standards**
  - [The POSIX standard (POSIX.1-2008)](http://pubs.opengroup.org/onlinepubs/9699919799/)
* **Git**
  - [Git home page](https://git-scm.com)
  - [Git official documentation](https://git-scm.com/doc)
  - [Good resources for learning Git and Github](https://help.github.com/articles/good-resources-for-learning-git-and-github/)
  - [15-minute tutorial in your browser](https://try.github.io)
  - [Video introduction](https://git-scm.com/videos)
  - [Student developer pack](https://education.github.com/pack) <br/> Get free
  stuff from GitHub Education, including a GitHub account with unlimited
  private repositories (normally 7$/month)
