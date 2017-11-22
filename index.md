---
layout: default
title: Home
---
# Introduction


<p class="lead">
This module introduces the application and implementation of operating
systems and the use of concurrency in systems programming. It presents
fundamental concepts: processes, communication and synchronisation,
and illustrates their implementation using a modern
OS.
</p>

<img src="assets/images/kf5010_image.png" alt="KF5010 tools" class="img-responsive center-block"/>


Students are given the opportunity to apply an OS in their own
programs to solve a variety of problems. Additional topics such as
memory management, file systems and security are required in the
implementation of a full-scale OS and are investigated in this module.

Lectures are the main vehicle for introducing fundamental concepts and
principles and for providing context and motivation. Students will be
expected to prepare for lecture topics and deepen their understanding
of course material by studying course texts and technical
literature. Seminars and laboratory sessions support the lecture
programme by providing students with opportunities to identify and
apply appropriate techniques for the application and implementation of
a variety of OS services.


Formative assessment will be provided in the form of small weekly
exercises, mainly practical in nature and involving
programming. Summative assessment is by way of a single piece of
coursework comprising a programming assignment and a short report.

# Module Team

|   |    |
|---|:---|
|Module Tutor &nbsp;  | [David Kendall](http://computing.northumbria.ac.uk/staff/cgdk2)|
|Lecturer      | [Michael Brockway](http://computing.northumbria.ac.uk/staff/cgmb3)|
|Lecturer      | [Alun Moon](http://computing.northumbria.ac.uk/staff/cgam1)|
|Lecturer      | [Nanlin Jin](https://www.northumbria.ac.uk/about-us/our-staff/j/nanlin-jin/)|
|TA      | [Ranjith Dinakaran](mailto:ranjith.dinakaran@northumbria.ac.uk)



# Teaching Arrangements

|   |    |
|---|:---|
**Lecture (Block A)** &nbsp;| Mon 12.00 - 13.00 LIP 031
**Lecture (Block B)** | Tue 14.00 - 15.00 LIP 031
**Lab/Seminar**       | Mon 09.00 - 11.00 PB S2
**Lab/Seminar**       | Tue 09.00 - 11.00 PB S2
**Lab/Seminar**       | Wed 09.00 - 11.00 PB S2
**Lab/Seminar**       | Wed 11.00 - 15.00 PB S2
**Lab/Seminar**       | Thu 12.00 - 14.00 PB S2
**Lab/Seminar**       | Fri 09.00 - 11.00 PB S2
**Lab/Seminar**       | Fri 11.00 - 13.00 PB S2
**Lab/Seminar**       | Fri 15.00 - 17.00 PB S2

<p class="text-info">
You should attend <em>both</em> lecture sessions and <em>one</em> of the
lab/seminar sessions every week. Refer to your personal timetable to identify
the lab session that you should attend.
</p>

# Synopsis


The aim of the module is to introduce operating system concepts and
the principles of concurrency, and to develop a practical
understanding of their implementation and application in modern
computing systems. Assessment is by course work.

On completion of this module, it is expected that students will be able to:



1. Describe the architecture of an operating system (OS) and its
services, and evaluate its use in a variety of scenarios.

2. Discuss the process model and the scheduling, IPC and
synchronisation services provided by an OS and reason informally about
the behaviour of a multitasking system under a variety of
scheduling algorithms.

3. Review the principal concepts and methods of memory management
and file system implementation.

4. Identify a variety of security threats and examine appropriate OS
mechanisms to protect against them.

5. Design, implement and evaluate solutions to problems of I/O
device handling, synchronisation, communication and timing for
multitasking systems, using appropriate OS services and concurrent
programming techniques.

# Teaching Plan

The following is a *provisional* guide to the organisation of
this part of the module for this year. These arrangements are subject to
change during the course of the module.


| Week   | W/c   | Lecture A   | Lecture B   | Practical   |
| :----: | :---: | :---------: | :---------: | :---------: |
**1** | 18-Sep &nbsp; | [Introduction and overview]({{site.raurl}}/A01.pdf) &nbsp; | [Introduction to Unix/Linux. Linux Command Line]({{site.raurl}}/B01.pdf) &nbsp; <br/> Reading: [SHO16, Chp. 1-6, 9]({{site.raurl}}/TLCL.pdf)| [Introduction to Lab environment and tools](L01.html)
**2** | 25-Sep &nbsp; | [Process concept]({{site.raurl}}/A02.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 4](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-intro.pdf)| [Shell scripts]({{site.raurl}}/B02.pdf) &nbsp; <br/> Reading: [SHO16, Chp. 24, 25, 27]({{site.raurl}}/TLCL.pdf)| [Learning the Linux command line](L02.html)
**3** | 02-Oct &nbsp; | [Process scheduling]({{site.raurl}}/A03.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 7](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)| [Linux processes]({{site.raurl}}/B03.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 5](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf)| [Writing shell scripts](L03.html)
**4** | 09-Oct &nbsp; | [Memory management&nbsp;1]({{site.raurl}}/A04.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 13](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)| [POSIX Threads: create, exit, join, self]({{site.raurl}}/B04.pdf) &nbsp; <br/> Reading: [AD-15 Chp. 27.1-27.2](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf) | [Shell functions. Working with processes](L04.html)
**5** | 16-Oct &nbsp; | [Memory management&nbsp;2]({{site.raurl}}/A05.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 15](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-mechanism.pdf) | [Interference, Race Conditions, Mutual Exclusion]({{site.raurl}}/B05.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 26](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf) | [Using the POSIX Threads API: create, exit, join, self](L05.html)
**6** | 23-Oct &nbsp; | [Memory management&nbsp;3]({{site.raurl}}/A06.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 15](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-mechanism.pdf)| [POSIX semaphores]({{site.raurl}}/B06.pdf) &nbsp; <br/> Reading: [A-D15 Chp. 31](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf) | [Mutual exclusion (Busy Waiting), Speedup](L06.html)
**7** | 30-Oct &nbsp; | [Storage management&nbsp;1]({{site.raurl}}/A07.pdf) &nbsp; <br/> Reading: [AD-15 Chp. 39](http://pages.cs.wisc.edu/~remzi/OSTEP/file-intro.pdf) | [Classical problems of synchronisation: producer/consumer, readers/writers]({{site.raurl}}/B07.pdf) &nbsp; <br/> Reading: SGG13 Chp. 5.7| [Mutual exclusion (Semaphores), Amdahl's Law](L07.html) <br/> Introduction to the assignment
**8** | 06-Nov &nbsp; | [Storage management&nbsp;2]({{site.raurl}}/A08.pdf) &nbsp; <br/> Reading: [AD-15 Chp. 40](http://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf) | [Monitors with Mutexes and Condition Variables]({{site.raurl}}/B08.pdf) &nbsp; <br/> Reading: [AD-15 App. Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf), SGG13 Chp. 5.8 | [Semaphores for synchronisation](L08.html)
**9** | 13-Nov &nbsp; | [Protection and security&nbsp;1]({{site.raurl}}/A09.pdf) &nbsp; <br/> Reading: SGG13 Chp.&nbsp;14 | [Deadlock, Starvation]({{site.raurl}}/B09.pdf) &nbsp; <br/>Reading: [AD-15 Chp. 32](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf), SGG13 Chp. 7.1-7.4  | [Monitors for synchronisation](L09.html)
**10** | 20-Nov &nbsp; | [Protection and security&nbsp;2]({{site.raurl}}/A10.pdf) &nbsp; | [Thread scheduling, Priority inversion]({{site.raurl}}/B10.pdf) &nbsp; | [Deadlock and starvation](L10.html)
**11** | 27-Nov &nbsp; | [Inside the Linux Kernel]({{site.raurl}}/A11.pdf) &nbsp; | [Dynamic memory management]({{site.raurl}}/B11.pdf) &nbsp; | [Thread scheduling, Mutex attributes](L11.html)
**12** | 04_Dec &nbsp; | Assignment support | Assignment support | Assignment support

<br/>

<p class="text-info">
In addition to the taught sessions, you are expected to undertake
independent and directed learning. This is a 20-credit module, for
which the expected student workload is 200 hours. Over the course of a
15-week semester, you should be spending about 13 hours per week on
this module.
</p>

# Assessment

Summative assessment comprises:

* a single course work assignment undertaken in the last 4/5 weeks of
the module; students will be required to:
  + implement a simple application, making use of operating system services,
  + to report on possible extensions to, and issues raised by, their work,
  + and to discuss relevant underlying OS theory. <br/> <br/>

<a class="btn btn-large btn-primary" href="{{site.raurl}}/assgn.pdf"><i class="icon-upload-alt"></i>Download Assignment Specification</a>

Formative assessment comprises a variety of theoretical and practical
exercises with opportunities for discussion with tutors and
colleagues.

Feedback on formative assessment will be given during the seminar and
laboratory sessions. Additionally, email will be used
for more formal feedback on summative assessment.

# Recommended Reading

There is no essential textbook for this module. [SGG13] is an excellent
introduction to operating systems in general and can be used to supplement the
slides for the Lecture A stream of the module. [A-D15] also covers much of this
material and has the advantage of being available *free online*.  The other
recommended books and papers give useful information on parts of the syllabus
only.


* **Books**
  - **[SGG13]** Silberschatz, A., Galvin, P., and Gagne,
G., [Operating System Concepts](https://www.amazon.co.uk/Operating-System-Concepts-Abraham-Silberschatz/dp/1118093755/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1505287999&amp;sr=1-1&amp;keywords=silberschatz+operating), John Wiley &amp; Sons, 9th edition, 2013, ISBN-13: 978-1118093757

  - **[A-D15]** Arpaci-Dusseau, R. and Arpaci-Dusseau, A., [Operating systems: Three easy pieces](http://www.ostep.org), Arpaci-Dusseau Books, 2015

  - **[DOW08]** Downey, A., [The Little Book of
Semaphores](http://www.greenteapress.com/semaphores/) ([Local copy]({{site.raurl}}/downey08semaphores.pdf)), Green Tea Press, 2002 <br/> A free text book by Allen Downey that introduces a variety of interesting synchronisation
problems and their solution using semaphores.

  - **[SHO16]** Shotts. W., [The Linux Command Line](http://linuxcommand.org/tlcl.php) ([Local copy]({{site.raurl}}/TLCL.pdf)), No Starch Press, 2016 <br/> A free text book by William Shotts on using the Linux command line.

# Resources

* **Programming in C**
  - **[KOC04]** Kochan, S., [Programming in C](http://www.amazon.co.uk/Programming-Developers-Library-Stephen-Kochan/dp/0672326663/ref=sr_1_5?ie=UTF8&amp;qid=1316089219&amp;sr=8-5), Sams, 2004 <br/>
A gentle introduction to programming in C. I think it's a better starting
point than the much-recommended Kernighan and Ritchie.

  - **[PRI02]** Prinz, P., [C Pocket Reference](http://www.amazon.co.uk/C-Pocket-Reference-Peter-Prinz/dp/0596004362/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1285570456&amp;sr=1-1), O'Reilly, 2002 <br/>
A concise C reference. Very cheap. Less than a fiver the last time I
looked. I suggest you buy a copy and read it from cover to cover.
  - [Essential C](http://cslibrary.stanford.edu/101/EssentialC.pdf), Parlante, N, Stanford University, 2003 <br/>
A very good summary of the basic features of the C language.
  - [Learn C Programming](http://tutorialspoint.com/cprogramming/) <br/> A nice online C programming tutorial site.
  - [C Programming](http://www.imada.sdu.dk/~svalle/courses/dm14-2005/mirror/c/) <br/>
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
