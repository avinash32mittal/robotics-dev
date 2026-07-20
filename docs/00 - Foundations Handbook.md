# Foundations Handbook

**Version:** 1.0\
**Current Curriculum:** Phase 1

------------------------------------------------------------------------

# Purpose

This handbook provides the foundational knowledge required before
learning Linux, programming, robotics, embedded systems, and AI. It
explains how computers work, how engineers think, and the core concepts
that every robotics engineer should understand.

------------------------------------------------------------------------

# Learning Philosophy

Throughout this curriculum:

-   Learn from first principles.
-   Understand *why* before *how*.
-   Relate every concept to robotics.
-   Build intuition before memorizing syntax.

------------------------------------------------------------------------

# Computer System Overview

A computer consists of:

  Component        Purpose
  ---------------- ---------------------------
  CPU              Executes instructions
  RAM              Temporary working memory
  Storage          Permanent data storage
  Motherboard      Connects hardware
  Input Devices    Keyboard, mouse, sensors
  Output Devices   Monitor, motors, speakers

Robotics Example: A robot continuously reads sensor inputs, processes
them using the CPU, stores temporary values in RAM, and sends commands
to actuators.

------------------------------------------------------------------------

# Hardware vs Software

## Hardware

Physical components you can touch.

Examples:

-   CPU
-   RAM
-   SSD
-   Camera
-   Motor Driver

## Software

Instructions executed by hardware.

Examples:

-   Ubuntu
-   Python
-   ROS 2
-   VS Code

------------------------------------------------------------------------

# Operating System

An Operating System (OS) manages hardware resources and provides
services for software.

Examples:

-   Ubuntu Linux
-   Windows
-   macOS

In robotics, Linux is the industry standard because it is stable,
flexible, and works well with ROS 2.

------------------------------------------------------------------------

# Files, Folders and Paths

Everything in Linux is organized as files and directories.

Example:

``` text
/home/avinash/robotics-dev/docs
```

Absolute paths start from the root (`/`).

Relative paths start from your current working directory.

------------------------------------------------------------------------

# Programming Fundamentals

## What is a Program?

A program is a sequence of instructions executed by the computer.

Example:

``` python
print("Hello Robotics")
```

------------------------------------------------------------------------

## Algorithm

An algorithm is a step-by-step procedure for solving a problem.

Robot Example:

1.  Read camera
2.  Detect object
3.  Calculate position
4.  Move robot arm
5.  Verify result

------------------------------------------------------------------------

## Variables

Variables store values that may change while a program executes.

``` python
battery_voltage = 48.2
motor_speed = 1500
```

Robotics examples:

-   Battery voltage
-   Wheel speed
-   Robot position
-   Temperature

------------------------------------------------------------------------

## Data Types

  Type    Example
  ------- ---------
  int     10
  float   10.5
  bool    True
  str     "Robot"

Choose the correct type to avoid bugs and wasted memory.

------------------------------------------------------------------------

## Input and Output

Input:

``` python
name = input("Enter name: ")
```

Output:

``` python
print(name)
```

Robotics input may come from sensors instead of a keyboard.

------------------------------------------------------------------------

## Control Flow

Programs make decisions using conditions.

``` python
if temperature > 80:
    print("High Temperature")
```

Loops repeat work.

``` python
for i in range(5):
    print(i)
```

Robots continuously run control loops until shut down.

------------------------------------------------------------------------

## Functions

Functions organize reusable code.

``` python
def calculate_area(l, b):
    return l * b
```

Benefits:

-   Reusability
-   Easier testing
-   Cleaner code

------------------------------------------------------------------------

## Collections

### List

``` python
temps = [45, 47, 46]
```

### Tuple

``` python
position = (10, 20)
```

### Dictionary

``` python
robot = {
    "name": "R1",
    "battery": 92
}
```

------------------------------------------------------------------------

## Modules

Modules allow code reuse.

``` python
import math
print(math.sqrt(25))
```

------------------------------------------------------------------------

## Errors and Exceptions

Syntax Error

``` python
print("Hello"
```

Runtime Error

``` python
10 / 0
```

Handling exceptions

``` python
try:
    value = int(input())
except ValueError:
    print("Invalid number")
```

------------------------------------------------------------------------

# Engineering Best Practices

-   Write readable code.
-   Name variables clearly.
-   Keep functions small.
-   Test frequently.
-   Use Git for version control.
-   Document your work.

------------------------------------------------------------------------

# Robotics Connection

Everything in later handbooks depends on these concepts.

Linux → Programming → Mathematics → Systems → Robotics → AI

------------------------------------------------------------------------

# Quick Reference

  Concept      Key Idea
  ------------ ------------------------
  Variable     Stores data
  Function     Reusable block of code
  List         Ordered collection
  Dictionary   Key-value mapping
  Loop         Repeats work
  Condition    Makes decisions
  Module       Reusable library
  Exception    Handles runtime errors

------------------------------------------------------------------------

# Next Handbook

Continue with **01 - Linux Handbook**.
