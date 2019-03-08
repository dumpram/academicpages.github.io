---
title: "Implementation of industrial embedded systems on Cortex-R platforms"
collection: topics
permalink: /topics/cortex-r
excerpt: 'Cortex-R architecture and safety-critical embedded system design.'
date: 2019-03-08

---

## Area overview

Alongside real-time constraints, industrial embedded systems have functional 
safety constraints. To resolve issue of safety certification many features are 
added to processor hardware design to ensure correct operation of system. These
features typically mitigate effects of radiation-induced errors. Embedded 
platforms with such hardware design contain:

* memory elements with ECC protection,
* lock-step processor architecture,
* secure processor operating modes.

Platforms of interest are:

* TI Hercules TMS570 series microcontroller systems,
* XCZU9EG (Zynq UltraScale+ ZCU102).

These platforms implement ARMv7-R architecture, Cortex-R processor profile
which contains features mentioned above.

## Project goal

Goal is to investigate following topics:

* Cortex-R and Cortex-M processor profiles and implementations,
* performance comparison of Cortex-R and Cortex-M processors,
* investigate safety features of Cortex-R platforms.

Goal is to develop following features:

* develop library for different industrial bus protocols on Cortex-R platforms,
* enable running different operating systems on Cortex-R platform,
* evaluate operating system performance. 

In the end, simulate typical industrial real-time application 
with connection of multiple slave units over CAN, FlexRay and similar buses.

## Requirements

* C
* Microcontroller programming
