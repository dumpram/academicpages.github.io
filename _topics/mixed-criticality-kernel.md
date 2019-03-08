---
title: "Mixed-criticality kernel for fault-tolerant real-time embedded systems"
collection: topics
permalink: /topics/mixed-criticality-kernel
excerpt: 'Mixed-criticality kernel design for MCU platforms.'
date: 2019-03-08

---

## Area overview 

Alongside real-time constraints, embedded systems today have functional safety
constraints. Additionally, embedded systems today are based on 
SoCs which include multicore application processors. To reconcile
all these constraints and to achieve maximum system utilization, 
mixed-criticality scheduling theory emerged. Mixed-criticality scheduling 
and accompanying fault-tolerant mechanisms can be used in development
of fault-tolerant real-time kernels which could be used in automotive, avionics
and railway control systems. 

## Project goal

Goal of the project is to develop mixed-criticality kernel for fault-tolerant 
embedded systems. Kernel needs to have classical real-time operating system 
features such as:

* interrupt management
* memory management
* timer management
* multitasking (basic preemptive fixed priority scheduler) 

Additionally, kernel needs to have mixed-criticality schedulers such as:

* static mixed-criticality assignment
* criticality monotonic priority assignment
* adaptive mixed criticality assignment
* EDF-VD assignment

Kernel needs to include fault-tolerant schemes for increase of task success
rate:

* sanity checks
* task replication

To implement any of additional features, kernel should be able to monitor 
fault state and execution time of each task. Target architectures are ARMv7-R 
and ARMv7-M.

## Requirements

Requirements:

* C
* microcontroller programming
