---
layout: section
title: ARCHER2 Training Courses
summary: ARCHER2 Training Courses
---

# ARCHER2  Training Courses



##  Outline Course Descriptions

<a href="#introductory">&nbsp;</a>
### Introductory (level 1) courses

* [Data Carpentry](#data_carpentry)
* [HPC Carpentry](#hpc_carpentry)
* [Software Carpentry](#software_carpentry)
* [Package Use on ARCHER2](#package_use)
* [Data Science on ARCHER2](#data_science)
* [Development on ARCHER2](#development)


<a href="#intermediate">&nbsp;</a>
### Intermediate (level 2) courses

* [Understanding Package Performance](#understanding_package_performance)
* [Data Analysis using Python](#data_analysis_using_python)
* [Containers for HPC](#containers_for_hpc)
* [Data Analytics with HPC](#data_analytics_with_hpc)
* [Message Passing Programming with MPI](#mpp_with_mpi)
* [Shared Memory Programming with OpenMP](#openmp)

<a href="#advanced">&nbsp;</a>
### Advanced (level 3) courses

* [Efficient Parallel IO](#efficient_parallel_io)
* [Performance Optimisation on AMD EPYC](#performance_optimisation_on_amd_epyc)
* [Performance Analysis Workshop](#performance_analysis_workshop)


<p><a name="introductory">&nbsp;</a></p>
### Introductory (level 1) courses

<p><a name="data_carpentry">&nbsp;</a></p>
#### Data Carpentry

In many domains of research, the rapid generation of large amounts of data is fundamentally changing how research is done. The deluge of data presents great opportunities, but also many challenges in managing, analysing and sharing data. Data Carpentry aims to teach the skills that will enable researchers to be more effective and productive. The course is designed for learners with little to no prior knowledge of programming, shell scripting, or command line tools. 


<p><a name="hpc_carpentry">&nbsp;</a></p>
#### HPC Carpentry

This course provides an introduction to High Performance Computing (HPC). After completing this course, participants will:

*    Understand motivations for using HPC in research
*    Understand how HPC systems are put together to achieve performance and how they differ from desktops/laptops
*    Know how to connect to remote HPC systems and transfer data
*    Know how to use a scheduler to work on a shared system
*    Be able to use the Bash command line on remote systems
*    Be able to use software modules to access different HPC software
*    Be able to work effectively on a remote shared resource

<p><a name="software_carpentry">&nbsp;</a></p>
#### Software Carpentry

Software Carpentry's goal is to help scientists and engineers become more productive by teaching them basic computing skills like program design, version control, testing, and task automation. In this two-day workshop, short tutorials will alternate with hands-on practical exercises. Participants will be encouraged both to help one another, and to apply what they have learned to their own research problems during and between sessions. 

<p><a name="package_use">&nbsp;</a></p>
#### Package Use on ARCHER2

This course will cover efficient use of pre-installed research software packages on ARCHER2. This will include the essentials of the ARCHER2 service and explain how pre-installed software packages can be used. We will run this both online and face-to-face and both of these will have practical exercises to complete.

<p><a name="data_science">&nbsp;</a></p>
#### Data Science on ARCHER2

This course will cover the essentials of ARCHER2, the basic use of core data science packages (e.g. R, Pandas), and data handling best practice.

<p><a name="development">&nbsp;</a></p>
#### Development on ARCHER2

This course will cover the ARCHER2 application development environment, core parallel and scientific software libraries, available debugging and profiling tools. This will be available both online and face-to-face course to suit the needs of attendees.


<p><a name="intermediate">&nbsp;</a></p>
### Intermediate (level 2) courses

<p><a name="understanding_package_performance">&nbsp;</a></p>
#### Understanding Package Performance

As parallel packages for computational science become more sophisticated, it becomes more difficult for a researcher to understand the most important factors that determine end-to-end productivity from initial input data to final result. Aspects such as file IO and data transfer can be just as important in practice as the performance and parallel scalability of the application itself. This course will take a holistic approach and cover tools and techniques to help researchers to improve their overall scientific productivity on large-scale HPC systems.

<p><a name="data_analysis_using_python">&nbsp;</a></p>
#### Data Analysis using Python

Data Analytics, Data Science and Big Data are a just a few of the many terms used in business and academic research, all referring to the manipulation, processing and analysis of data. Fundamentally, these are all concerned with the extraction of knowledge from data that can be used for competitive advantage or to provide scientific insight. In recent years, this area has undergone a revolution in which HPC has been a key driver. This course provides an overview of data science and the analytical techniques that form its basis as well as exploring how HPC provides the power that has driven their adoption. The course will cover: key data analytical techniques such as, classification, optimisation, and unsupervised learning; key parallel patterns, such as Map Reduce, for implementing analytical techniques; relevant HPC and data infrastructures; case studies from academia and business.

<p><a name="containers_for_hpc">&nbsp;</a></p>
#### Containers for HPC

This course aims to introduce the use of Docker containers with the goal of using them to effect reproducible computational environments. Such environments are useful for ensuring reproducible research outputs and for simplifying the setup of complex software dependencies across different systems. We will also briefly introduce the Singularity container environment which is compatible with Docker and designed for use on multi-user systems (such as HPC resources).

<p><a name="data_analytics_with_hpc">&nbsp;</a></p>
#### Data Analytics with HPC

Data Analytics, Data Science and Big Data are a just a few of the many terms used in business and academic research, all referring to the manipulation, processing and analysis of data. Fundamentally, these are all concerned with the extraction of knowledge from data that can be used for competitive advantage or to provide scientific insight. In recent years, this area has undergone a revolution in which HPC has been a key driver. This course provides an overview of data science and the analytical techniques that form its basis as well as exploring how HPC provides the power that has driven their adoption. The course will cover: key data analytical techniques such as, classification, optimisation, and unsupervised learning; key parallel patterns, such as Map Reduce, for implementing analytical techniques; relevant HPC and data infrastructures; case studies from academia and business.

<p><a name="mpp_with_mpi">&nbsp;</a></p>
#### Message Passing Programming with MPI

The world's largest supercomputers are used almost exclusively to run applications which are parallelised using Message Passing. This course covers all the basic knowledge required to write parallel programs using this programming model, and is directly applicable to almost every parallel computer architecture.

Parallel programming by definition involves co-operation between processors to solve a common problem. The programmer has to define the tasks that will be executed by the processors, and also how these tasks are to synchronise and exchange data with one another. In the message-passing model the tasks are separate processes that communicate and synchronise by explicitly sending each other messages. All these parallel operations are performed via calls to some message-passing interface that is entirely responsible for interfacing with the physical communication network linking the actual processors together. This course uses the de facto standard for message passing, the Message Passing Interface (MPI). It covers point-to-point communication, non-blocking operations, derived datatypes, virtual topologies, collective communication and general design issues.

The course is taught using a variety of methods including formal lectures, practical exercises, programming examples and informal tutorial discussions. This enables lecture material to be supported by the tutored practical sessions in order to reinforce the key concepts.

<p><a name="openmp">&nbsp;</a></p>
#### Shared Memory Programming with OpenMP

Almost all modern computers now have a shared-memory architecture with multiple CPUs connected to the same physical memory, for example multicore laptops or large multi-processor compute servers. This course covers OpenMP, the industry standard for shared-memory programming, which enables serial programs to be parallelised easily using compiler directives. Users of desktop machines can use OpenMP on its own to improve program performance by running on multiple cores; users of parallel supercomputers can use OpenMP in conjunction with MPI to better exploit the shared-memory capabilities of the compute nodes.

This course will cover an introduction to the fundamental concepts of the shared variables model, followed by the syntax and semantics of OpenMP and how it can be used to parallelise real programs. Hands-on practical programming exercises make up a significant, and integral, part of this course.

<p><a name="advanced">&nbsp;</a></p>
### Advanced (level 3) courses


<p><a name="efficient_parallel_io">&nbsp;</a></p>
#### Efficient Parallel IO

One of the greatest challenges to running parallel applications on large numbers of processors is how to handle file IO: standard IO routines are not designed with parallelism in mind. Parallel file systems such as Lustre are optimised for large data transfers, and performance can be far from optimal if many files are opened at once.

The IO part of the MPI standard gives programmers access to efficient parallel IO in a portable fashion. However, there are a large number of different routines available and some can be difficult to use in practice. Despite its apparent complexity, MPI-IO adopts a very straightforward high-level model. If used correctly, almost all the complexities of aggregating data from multiple processes can be dealt with automatically by the library.

The first day of the course will cover the MPI-IO standard, developing IO routines for a regular domain decomposition example. It will also briefly cover higher-level standards such as HDF5 and NetCDF. The second day will concentrate on how to use the Lustre file system for best performance. Case studies from real codes will also be presented.

Although the course mainly uses the MPI-IO library and the Lustre parallel filesystem for specific examples, most of the IO concepts and performance considerations are applicable to almost any parallel system.

<p><a name="performance_optimisation_on_amd_epyc">&nbsp;</a></p>
#### Performance Optimisation on AMD EPYC

This course covers the system-specific features of the ARCHER2 processing units over two days. It includes a detailed overview of the AMD EPYC processors and Cray-provided systems software and performance tools. It is ideal for users both familiar with existing Cray supercomputers or those porting from alternative platforms.

<p><a name="performance_analysis_workshop">&nbsp;</a></p>
#### Performance Analysis Workshop

Current and future supercomputing architectures face a dramatic growth of parallelism and heterogeneity on multiple levels. As a result, it is almost impossible for code developers to predict which parts of their code will perform well, which development decisions impact scalability, which choice of data structures are reasonable for a specific architecture, etc. Most decisions are based upon experience, intuition and a limited understanding of the code's performance.

To get a better understanding of code performance and to guide performance engineering, it is essential for computational scientists and engineers to conduct measurements in order to study code performance in detail. Performance analysis tools, a generalisation of the classic profiler, are the best tools to obtain this insight. However, they themselves require a certain level of understanding, experience and expertise to be used productively which adds to the complexity of the underlying problem. This workshop introduces several performance analysis tools and provides hands-on training on how to use them in practice on large-scale HPC applications.