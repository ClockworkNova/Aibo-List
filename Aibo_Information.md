---
title: Restoring the Sony Aibo
---

History of the Sony Aibo
========================

AIBO (stylized aibo, Artificial Intelligence Robot, homonymous with aibō (相棒),
"pal" or "partner" in Japanese) was a series of robotic pets designed and
manufactured by Sony.

Although most models were dog-like, other inspirations included lion-cubs and
space explorer, and only the ERS-7 version and ERS-1000 versions was explicitly
a "robotic dog". In 2006, AIBO was added into the Carnegie Mellon University
Robot Hall of Fame. On 26 January 2006 Sony announced that it would discontinue
AIBO and several other products in an effort to make the company more
profitable.[5] Sony's AIBO customer support was withdrawn gradually, with
support for the final ERS-7M3 ending in March 2013. In July 2014, Sony stopped
providing repairs for AIBO products and did not provide customer support or
repair for AIBO robots.

Source: <https://en.wikipedia.org/wiki/AIBO>

About this repository:
======================

This repository is an effort to restore / reverse engineer and breathe new life
to the Sony Aibo. Since it contains a lot of proprietary elements, there are a
lot of things that will need to be re-designed, improved and even reinvented.

How can you help?
-----------------

Any help that you can give in any way will be appreciated. This can range from
more information, design support, expertise in electronics etc and any other
help at all. Some of the main points are as follows:

-   Replicate and improve on mechanical aspects through 3D printing.

    -   Improve on strength and durability

    -   Improve upon factory mechanical weaknesses

    -   Add stronger servos- current ones harmed with repetitive quick movements

-   Import or replicate core code for replacement CPUs.

    -   Improve on CPU memory and power if possible

-   Improve on unit cooling if possible (only one model has an internal fan).

-   Improve on unit vision if possible- current digital camera vision results in
    blurry photos and difficulties with facial recognition.

-   Possibly make memory data compatible with SD cards. Unit memory is currently
    stored in aging Sony Memory Sticks.

Important Links to start with:
------------------------------

<http://www.dogsbodynet.com/aibnet.html>

Aibnet & its support tools offers a development environment for RCode programs.

<http://www.dogsbodynet.com/aibnet_tools/BeCompile.html>

BeCompile is an optimizing compiler, which generates smaller & more efficient
RCode from Master Studio Behavior Arranger files. It optionally comments the
RCode (for readability), uses readable labels for groups, collapses conditional
statements, eliminates duplicate code where possible, checks for uninitialized
variables (or variable names differing only by case), plus much more!

<http://www.dogsbodynet.com/aibnet_tools/CPP.html>

CPP is a macro preprocessor. The tool originated many years ago to when the C
programming language was first developed. CPP fortunately works with any
language, not just C, and therefore helps us write better RCode. This version of
CPP was created by Sun Microsystems, and modified slightly (to display a help
screen from the command line, and support DOS pathname conventions). Source code
is available upon request.

<http://www.dogsbodynet.com/aibnet_tools/RCheck.html>

RCheck performs syntax checks on RCode programs.

<http://www.dogsbodynet.com/openr.html>

R-code Intro

<http://www.dogsbodynet.com/rcode.html>

R-Code Files and Info

<http://www.aibohack.com/210/hardware.htm>

Core internals of a 210 unit

<http://www.aibohack.com/310/hardware.htm>

Core internals of a 310 unit

<https://aibodoctor.com/manuals/>

Aibo manuals. Repair guides not reliable, though present a look into the
internals

<https://dasisolutions.com/3d-cad-2/item/how-i-saved-my-robot-dog-s-life>

Instance of improving and printing a broken part using an interesting tool

<http://www.yk.rim.or.jp/~hkora11/aibo_ers-310/index.html>

Apparently this is a good japanese source for the internals.
