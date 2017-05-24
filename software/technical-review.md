# Technical Review

This documents the core interfaces of the software

**Contents:**

- Overview
- Game Device
- Arduino output
- Fitboard Input reading for Unity

### Overview

The Fitboard circuitry is hooked up to an Arduino Mega (arduino) (TODO link specs).

The arduino writes the values of pressed buttons to the serial connection.

### Game Device

Generically *'Game Device'* refers to any device the ReGameVR application is being run on.

Currently the Game Device is a Windows Surface Pro Tablet running Windows 10 with an Arduino device driver installed.

### Arduino Output

The arduino is connected to the Game Device by a USB. The arduino
