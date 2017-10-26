# Learning-Path[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



Introduction
------------

这是一份**模式识别与机器学习**方面的自学计划，来源于网络上的mooc，包括课程的视频，讲义，笔记，作业及扩展阅读。

Table of Contents
-----------------

- [Introduction to CS](#introduction-to-cs)
- [Programming languages](#programming-languages)
- [Algorithms](#algorithms)
- [Systems](#systems)
- [Calculus](#calculus)
- [Probability & Statistics](#probability-and-statistics)
- [Linear Algebra](#linear-algebra)
- [Optimization Theory](#optimization-theory)
- [Numerical Analysis](#numerical-analysis)
- [Signal Processing](signal-processing)
- [Information Theory](#information-theory)
- [Cybernetic Theory](#cybernetic-theory)

### Legend

- <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4f9.png" width="20" height="20" alt="Lecture Videos" title="Lecture Videos" /> - Lecture Videos
- <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" /> - Lecture Notes
- <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> - Assignments / Labs
- <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4da.png" width="20" height="20" alt="Readings" title="Readings" /> - Readings


Courses
-------

### Introduction to CS

- [CS 61A](http://composingprograms.com/) **Structure and Interpretation of Computer Programs [Python]** *UC Berkeley*  <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4f9.png" width="20" height="20" alt="Lecture Videos" title="Lecture Videos" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" />
	- In CS 61A, we are interested in teaching you about programming, not about how to use one particular 	programming language. We consider a series of techniques for controlling program complexity, such as functional programming, data abstraction, and object-oriented programming. Mastery of a particular programming language is a very useful side effect of studying these general techniques. However, our hope is that once you have learned the essence of programming, you will find that picking up a new programming language is but a few days' work.
	- [Lecture Resources by Type](http://cs61a.org/by_type.html)
	- [Lecture Resources by Topic](http://cs61a.org/by_topic.html)
	- [Additional Resources](http://cs61a.org/articles/resources.html)
	- [Practice Problems](http://cs61a.org/problems/)
	- [Extra Lectures](http://cs61a.org/extra.html)
	
### Systems

- [CS 140](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/lectures.php) **Operating Systems** *Stanford University* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" />
	- This class introduces the basic facilities provided in modern operating systems. The course divides into three major sections. The first part of the course discusses concurrency. The second part of the course addresses the problem of memory management. The third major part of the course concerns file systems.
	- [Lecture Notes](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/lectures.php)
	- [Assignments](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/projects.php)
- [CS 168](https://inst.eecs.berkeley.edu/~cs168/fa14/) **Introduction to the Internet: Architecture and Protocols** *UC Berkeley* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" />
    - This course is an introduction to the Internet architecture. We will focus on the concepts and fundamental design principles that have contributed to the Internet's scalability and robustness and survey the various protocols and algorithms used within this architecture. Topics include layering, addressing, intradomain routing, interdomain routing, reliable delivery, congestion control, and the core protocols (e.g., TCP, UDP, IP, DNS, and HTTP) and network technologies (e.g., Ethernet, wireless).
    - [Lecture Notes & Assignments](https://inst.eecs.berkeley.edu/~cs168/fa14/class.html)
    - [Discussion Notes](https://inst.eecs.berkeley.edu/~cs168/fa14/)
- [CS 179](http://courses.cms.caltech.edu/cs179/) **GPU Programming** *Caltech*  <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" />
	- This course will cover programming techniques for the GPU. The course will introduce NVIDIA's parallel computing language, CUDA. Beyond covering the CUDA programming model and syntax, the course will also discuss GPU architecture, high performance computing on GPUs, parallel algorithms, CUDA libraries, and applications of GPU computing. 
	- [Assignments](http://courses.cms.caltech.edu/cs179/)
	- [Lecture Notes](http://courses.cms.caltech.edu/cs179/)
- [CS 186](https://sites.google.com/site/cs186spring2015/) **Introduction to Database Systems** *UC Berkeley* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4f9.png" width="20" height="20" alt="Lecture Videos" title="Lecture Videos" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4da.png" width="20" height="20" alt="Readings" title="Readings" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" />
	- In the project assignments in CS186, you will write a basic database management system called SimpleDB. For this project, you will focus on implementing the core modules required to access stored data on disk; in future projects, you will add support for various query processing operators, as well as transactions, locking, and concurrent queries.
	- [Lecture Videos](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iBVK2QzAV-R7NMA1ZkaiR2y)
	- [Lecture Notes](https://sites.google.com/site/cs186fall2013/section-notes)
	- [Projects](https://sites.google.com/site/cs186fall2013/homeworks)
- [6.828](http://pdos.csail.mit.edu/6.828/2014/) **Operating Systems** *MIT* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" />
	- MIT's operating systems course focusing on the fundamentals of OS design including booting, memory management, environments, file systems, multitasking, and more. In a series of lab assignments, you will build JOS, an OS exokernel written in C.
	- [Assignments](http://pdos.csail.mit.edu/6.828/2014/labguide.html)
	- [Lectures](http://pdos.csail.mit.edu/6.828/2014/schedule.html)
	- [Videos](http://pdos.csail.mit.edu/6.828/2011/schedule.html) Note: These are student recorded cam videos of the 2011 course. The videos  explain a lot of concepts required for the labs and assignments.
