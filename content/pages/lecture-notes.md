---
content_type: page
title: Lecture Notes
uid: 5816426e-e626-2b91-ed6f-aec27f48aba8
---

This course makes use of Athena, MIT's UNIX-based computing environment. OCW does not provide access to this environment.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
LECTURE NOTES
{{< thclose >}}
{{< thopen >}}
NOTES, SUPPORTING FILES, AND LINKS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1–2
{{< tdclose >}}
{{< tdopen >}}
Introduction: Problem formulation, algorithm development, algorithm implementation, and algorithm verification. Structure and documentation
{{< tdclose >}}
{{< tdopen >}}


Lec #1 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec01))

Lec #2 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec02))


{{< tdclose >}}
{{< tdopen >}}


### Lec #1

Class introduction; overview of languages; program development.

### Lec #2

Discussion of aspects of computers and their operation. An example is given of program development for a simple case of computing the area of a figure.

Links that are in the notes for this lecture:

[What is big-endian?](http://www.webopedia.com/TERM/B/big_endian.html)

[Green's Theorem](http://mathworld.wolfram.com/GreensTheorem.html)

[The IEEE standard for floating point arithmetic](http://www.dsc.ufcg.edu.br/~cnum/modulos/Modulo2/IEEE754_2008.pdf)

Minor links for those interested:

[Velocity Engine](https://velocity.apache.org/engine/1.7/)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3–7
{{< tdclose >}}
{{< tdopen >}}
FORTRAN: "Formula Translation". Program creation, compilation and linking, variables and parameters, flow control, subroutines and functions. Structure and documentation. Use of libraries, internal and external communication, and interaction with other languages. FORTRAN: implementation issues: compilation errors, segmentation violations, Not-a-Number (NaN), Input/Output (IOSTAT) errors, Runtime errors. Transportable code, standard extensions. FORTRAN 90 differences and similarities to FORTRAN 77
{{< tdclose >}}
{{< tdopen >}}


Lec #3 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec03))

Lec #4 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec04))

Lec #5 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec05))

Lec #6 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec06))

Lec #7 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec07))


{{< tdclose >}}
{{< tdopen >}}


### Lec #3

Started FORTRAN (Formula Translation). Went through the basic elements that make up this language. An on-line version of a FORTRAN 77 manual can be found [here](http://physik.uibk.ac.at/hephy/praktikum/fortran_manual.pdf). In reading these notes, you should think about operations you want to do and what command or commands do you use to do that. The list on FORTRAN intrinsic functions can be found [here](https://gcc.gnu.org/onlinedocs/gcc-3.4.6/g77/Table-of-Intrinsic-Functions.html).

Other links to look at:

[The FORTRAN Programming Language](https://ourcodingclub.github.io/tutorials/fortran-intro/)

[Wikipedia Definition of FORTRAN](http://en.wikipedia.org/wiki/Fortran)

### Lec #4

Continued with showing the elements of the FORTRAN and more detail on the typically encountered features of the language. Topics covered: subroutines and functions; intrinsic functions; constants and variables; input output with open/close, read/write, formats; character strings.

The links in this lecture were to FORTRAN and intrinsic functions, which are given above. The programs poly\_area.f ([F]({{< baseurl >}}/resources/poly_area)) and vars.f ([F]({{< baseurl >}}/resources/vars)) are also used. (To download programs, right click on link and "save link target as". With one-button mouse use \<ctrl>\<click> on link). On Athena to use these programs:

ssh –X linerva.mit.edu  
%add fortran  
%f77 poly\_area.f –o poly\_area  
% poly\_area

To use the f90 compiler on Athena, use add sunsoft.

Other sources of information:

[Safari Book Online](https://www.oreilly.com/library/view/learning-java-4th/9781449372477/pr02s07.html) - O'Reilly series of books on programming (available with MIT certificate)

[FORTRAN Resources](http://www.personal.psu.edu/faculty/h/d/hdk/fortran.html) - useful link with lots of information on FORTRAN in its various forms

### Lec #5

Continued with FORTRAN. Character strings, control statements if and do; other commands such as include, common, parameter. More programs will be developed in class including simple output and computing root-mean-square scatter of randomly generated numbers.

### Lec #6

Finish up FORTRAN. Compile, linking and runtime errors and miscellaneous topics. Practice with using the language.

### Lec #7

Examines the changes that were made in FORTRAN90 with the introductions on more modern concepts in programming languages.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8–11
{{< tdclose >}}
{{< tdopen >}}


C for scientific uses. Representation of data through arrays, pointers, and data structures. Function calls, argument passing and scoping rules, IO, profiling, system calls, and signals

C++ objects. Encapsulation and inheritance, polymorphic operators


{{< tdclose >}}
{{< tdopen >}}


Lec #8 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec08))

Lec #9 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec09))

Lec #10 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec10))

Lec #11 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec11))


{{< tdclose >}}
{{< tdopen >}}


### Lec #8

Start of C-language programming. History, variables and executable statements.

Basic C Lecture

Basic C: C and FORTRAN 77 Syntax

Basic C: New Features

Lec #08 Exercises.

### Lec #9

Continuation of C. Covering Examined C-pointer; file Input/Output and the routines for formatted reads and write; compiling C routines; the C preprocessor cpp; structures in C; memory management.

Lec09\_pnt.c ([C]({{< baseurl >}}/resources/lec09_pnt)) is demonstration of pointers

### Lec #10

Finish structures and memory management in C. Start of C++. Inheritance and overloading in C++.

C and C++ routines used in class launch.c ([C]({{< baseurl >}}/resources/launch-2))

Ball.h ([H]({{< baseurl >}}/resources/ball)) and launch.cc ([CC]({{< baseurl >}}/resources/launch))

C++ zip files:

ustring.zip ([ZIP]({{< baseurl >}}/resources/ustring)) (The ZIP file contains: 2 .h files, 1 .cc file, and 1 .txt file.)  
launch.zip ([ZIP]({{< baseurl >}}/resources/launch-1)) (The ZIP file contains: 1 .cc file, 1 .h file, and 1 .txt file.)  
coord.zip ([ZIP]({{< baseurl >}}/resources/coord)) (The ZIP file contains: 1 .cc file, 1 .h file, and 1 .txt file.)

### Lec #11

Finish up of C++ looking at classes, inheritance and overloading. We will look more carefully at the code linked in Lec #10. Homework number 3 has been set.

Example pieces of code for C and comparison to FORTRAN:

C basics ([PDF]({{< baseurl >}}/resources/mit12_010f11_c_basics)), area.c ([C]({{< baseurl >}}/resources/area)), hello.c ([C]({{< baseurl >}}/resources/hello))  
C FORTRAN compare ([PDF]({{< baseurl >}}/resources/mit12_010f11_c_fortan_comp))  
C pointers ([PDF]({{< baseurl >}}/resources/mit12_010f11_c_pointers))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12–13
{{< tdclose >}}
{{< tdopen >}}


Mathematica. What it is and what it can do; structure of Mathematica; symbols, exact numbers, and machine numbers; lists, vectors, and matrices

Working with Mathematica: numerical calculations, symbolic calculations, and graphics. Importing and exporting information


{{< tdclose >}}
{{< tdopen >}}


Lec #12 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec12))

Lec #13 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec13))


{{< tdclose >}}
{{< tdopen >}}


### Lec #12

Start of Mathematica. These lectures are accompanied by a Mathematica Notebook that shows example of concepts presented in the notes.

Lec 12 NB ([NB]({{< baseurl >}}/resources/12010lec12))

Introductory screen casts from Wolfram:

[Introduction](http://url.wolfram.com/oHLP0k/)

[Making Models](https://www.wolfram.com/broadcast/video.php?c=135&v=514)

[Use of the demonstrations site](https://demonstrations.wolfram.com/about.html)

[Featured Demonstrations](http://demonstrations.wolfram.com/index.html)

### Lec #13

Continuation of Mathematica. These lectures are accompanied by a Mathematica notebook that shows example of concepts presented in the notes.

Lec 13 NB ([NB]({{< baseurl >}}/resources/12010lec13))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14–17
{{< tdclose >}}
{{< tdopen >}}


MATLAB®. "Matrix Laboratory". MATLAB syntax, workspace, variables. Script M-files, IO, control flow, debugging, and profiling tools. Object-oriented programming

MATLAB applications, polynomials, interpolation, integration, differentiation, ODE. Graphics, 2-D, 3-D, Graphical User Interface (GUI)


{{< tdclose >}}
{{< tdopen >}}


Lec #14 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec14))

Lec #15 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec15))

Lec #16 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec16))

Lec #17 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec17))


{{< tdclose >}}
{{< tdopen >}}


### Lec #14

MATLAB: introductory lecture on MATLAB introducing system, variable types, control and functions. The following MATLAB M-files are used in the lecture:

Lec01\_01.m ([M]({{< baseurl >}}/resources/lec01_01))  
Lec01\_02.m ([M]({{< baseurl >}}/resources/lec01_02))

### Lec #15

MATLAB: path command, variables, file IO and dialog boxes. The following M-files are used:

Lec02\_01\_file.m ([M]({{< baseurl >}}/resources/lec02_01_file))  
Lec02\_02\_db.m ([M]({{< baseurl >}}/resources/lec02_02_db))  
Lec03\_01\_file.m ([M]({{< baseurl >}}/resources/lec03_01_file))

The data for these M-files can be found in [MatData](http://www-gpsg.mit.edu/~tah/12.010/MatData/). A tar file with the data is TSeries.tar ([TAR]({{< baseurl >}}/resources/tseries)) (The TAR file contains: 10 .dat1 files, 10 .dat2 files, and 10 .dat3 files.)

### Lec #16

MATLAB: graphics handles and animation of figures. The following M-files are used in class:

Lec03\_movie.m ([M]({{< baseurl >}}/resources/lec03_movie))  
MATLAB/per\_func.m ([M]({{< baseurl >}}/resources/per_func))

### Lec #17

MATLAB: final class on GUI construction and use. The following M-files are used (along with the data from [MatData](http://www-gpsg.mit.edu/~tah/12.010/MatData/): a tar file with the data is TSeries.tar ([TAR]({{< baseurl >}}/resources/tseries)) (The TAR file contains: 10 .dat1 files, 10 .dat2 files, and 10 .dat3 files.)

Basic GUI layout:

GPSanal.m ([M]({{< baseurl >}}/resources/gpsanal))  
gpsguio.m ([M]({{< baseurl >}}/resources/gpsguio))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18–19
{{< tdclose >}}
{{< tdopen >}}
Python scripting language program
{{< tdclose >}}
{{< tdopen >}}


Lec #18 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec18))

Lec #19 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec19))


{{< tdclose >}}
{{< tdopen >}}


### Lec #18

Python I: Python Language Basics

[Python Programming Language—Official Website](http://www.python.org/)  
[Python v2.7.3 documentation](http://docs.python.org/index.html)  
[The Python Tutorial](http://docs.python.org/tutorial/)

### Lec #19

Python II: Python Advanced Usage


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Advanced graphics in MATLAB, 3-D representation and exportable animations
{{< tdclose >}}
{{< tdopen >}}
Lec #20 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec20))
{{< tdclose >}}
{{< tdopen >}}


### Lec #20

3-D graphics in MATLAB.

Examples are:

Lec20\_3D.m ([M]({{< baseurl >}}/resources/lec19_3d))   
Lec20\_TotalANC.avi ([AVI](http://geoweb.mit.edu/~tah/12.010/Lec19_TotalANC.avi))   
Lec20\_RateANC.avi ([AVI](http://geoweb.mit.edu/~tah/12.010/Lec19_RateANC.avi))   
Dif\_1006\_0407.fig ([FIG](http://geoweb.mit.edu/~tah/12.010/Dif_1006_0407.fig))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Ordinary differential equation (ODE) solutions used MATLAB and Mathematica
{{< tdclose >}}
{{< tdopen >}}
Lec #21 ([PDF]({{< baseurl >}}/resources/mit12_010f11_lec21))
{{< tdclose >}}
{{< tdopen >}}


### Lec #21

Solution to differential equations in Mathematica and MATLAB.

Mathematic notebook: 12.010.Lec18\_NDsolve.nb ([NB]({{< baseurl >}}/resources/12010lec18_ndsolve))

MATLAB solutions are:

Lec21\_ODE.m ([M]({{< baseurl >}}/resources/lec18_ode))   
Lec21\_animate.m ([M]({{< baseurl >}}/resources/lec18_animate))   
Lec21\_hit.m ([M]({{< baseurl >}}/resources/lec18_hit))   
Lec21\_bacc.m ([M]({{< baseurl >}}/resources/lec18_bacc))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22–24
{{< tdclose >}}
{{< tdopen >}}


Advanced Topics: Parallel computing with large memory and large numbers of CPUs

Advanced topics: Parallel MATLAB

Discussion of final projects

**Order of the presentations will be decided in the last class**


{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}


### Lec #22

Introduction of class project. Graphics formats and issues about vector and pixel based graphics.

[GMT graphics package](http://gmt.soest.hawaii.edu/) for mapping applications

### Lec #23

Class projects: graphics processor unit (GPU) processing. Statistics and random number generators. M-file randtest.m ([M]({{< baseurl >}}/resources/randtest)) is implementation of an LCG random number generator.

### Lec #24

Graphics: review of common graphics program. Graphics with spreadsheets, Kaleidagraph, Generic Mapping Tool (GMT). Numerical methods: introduction to numerical methods

Statistical analysis tools including generation random variables and correlated random numbers

The order of the class presentations will be decided in this class and posted after the class.

[Cuda Zone](http://www.nvidia.com/object/cuda_get.html)

[MATLAB Implementation](http://www.accelereyes.com/)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Final Project Presentations
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}