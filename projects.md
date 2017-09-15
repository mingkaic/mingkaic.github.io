---
layout: default
title: Projects
permalink: /projects
---

<h3><a href="https://github.com/mingkaic/videar">Videar</a></h3>

Type: <a href="http://videar.videar.2a97f93d.svc.dockerapp.io/home">Website</a>

Status: July 2017 - Present

Technologies: 
- Javascript/Typescript (Angular4, Node, Express, Mongo, Chai)
- Docker, Java (Spring)
- CMUSphinx (Temporary 3rd party Speech to text)

Videar extracts and displays subtitles from audio files. 
The user has the option to synthesize short audio clips given a subtitle and a selection of uploaded audio assets.

<h3><a href="https://github.com/mingkaic/rocnnet">ROCNNet</a></h3>

Type: Library

Technologies: 
- C++ (CMake, Boost, GTest)
- Valgrind
- Travis-CI

August 2016 - Present

Rocnnet uses graph-based automatic differentiation to create a network of tensor calculations. 
Each series of calculations make up some perceptron or high-level machine learning construct.
Graph nodes hold intermediate values in-memory to exchange speed for memory.

<h3><a href="https://github.com/mingkaic/defector">Defector</a></h3>

Type: Development tool

Technologies:
- C++ (CMake, LLVM)
- Python (Theanos)

March-April 2017

Based on https://ece.uwaterloo.ca/~lintan/publications/deeplearn-icse16.pdf, Defector predicts source code defects using Deep Belief Network (a machine learning algorithm) on generated semantic features.
Source code defect is defined as any line, block, or function that can be labelled by a distinct issue.
