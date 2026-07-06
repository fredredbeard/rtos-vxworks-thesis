# Real-Time Operating Systems, with a Features and Performance Analysis of VxWorks

Bachelor's Thesis — Computer Science Degree Program
School of Mathematical, Physical and Natural Sciences, University of Florence
**Author:** Federico Lombardi · **Advisor:** Prof. Rosario Pugliese · A.Y. 2024-2025

## Description

Thesis on real-time operating systems (RTOS), with an in-depth analysis of **VxWorks** (Wind River Systems), a proprietary RTOS used in safety-critical sectors (aerospace, defense, automotive, motorsport).

## Contents

1. **Introduction** — thesis goals and structure.
2. **Real-time systems** — differences between soft/firm/hard real-time, key characteristics, common misconceptions, classification of scheduling algorithms.
3. **Scheduling algorithms for aperiodic tasks** — Jackson, Horn, Bratley, Spring algorithms, Latest Deadline First, EDF with precedence constraints.
4. **Scheduling algorithms for periodic tasks** — Rate Monotonic, Earliest Deadline First, Deadline Monotonic, RM vs EDF comparison.
5. **Real-Time Operating Systems** — RTOS organization, memory management (real/virtual address space, dynamic allocation, stack overflow checking), interrupt handling, task deadlines, priority inversion (priority ceiling, priority inheritance).
6. **VxWorks** — features (task/scheduling, synchronization, IPC, cross-compiled development environment, file systems), performance test design and results (task switching, preemption, interrupt latency, message communication, semaphore shuffling), comparison with other RTOS, real-world use cases:
   - NASA Mars Rover Curiosity
   - Leonardo S.p.A. (defense)
   - Formula 1 telemetry (Magneti Marelli)
7. **Conclusions and future developments** — multi-core RTOS, certification standards (ARINC653, AUTOSAR), RTOS security (SCADA, known vulnerabilities), integration with artificial intelligence.

## Files

`LombardiFederico.pdf` — full text (48 pages).
