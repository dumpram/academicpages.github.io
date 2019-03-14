---
title: "Implementation of TensorFlow models on FPGA platform"
collection: topics
permalink: /topics/tensorflow-fpga
excerpt: 'Design framework for adpating machine learning TensorFlow models for FPGA.'
date: 2019-03-08

---

## Project goal

Goal of the project is develop framework for adapting Tensorflow models for
implementation on FPGA hardware. Developed toolbox has to enable generation
of hardware description langauge code (VHDL or Verilog). Other tasks are:

* research of state-of-the-art models,
* determine MPSoC platform with FPGA for testing,
* demonstrate functionalities of developed toolbox on practical examples (classification),
* enable connection between generated IP blocks and Linux operating system
* compare performance of models generated using toolbox to their implementations for GPU.

## Requirements

Requirements:

* Python 
* machine learning
* VHDL, Verilog
