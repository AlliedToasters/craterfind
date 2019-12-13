# CRATERFIND (In Development)

This is a prototype application for AI-assisted "one-click" crater annotation by human annotators.

## Overview

CRATERFIND uses a neural network model to locate a crater given a rough crater location and an input image. This information is provided by an annotator with a single click. <br><br>
The model takes an array of 32x32 pixels and returns three values, a 3-point representation of a circle (x,y,r). Below is an example input and the output is overlaid on the input image.

![Input (raw pixels)](./content/input.png)
![Output (3-point circle)](./content/output.png)

## Purpose of This Repository

Much work is being done on solving this problem, but CRATERFIND works on the specific problem of integrating this technology with existing user interfaces.
