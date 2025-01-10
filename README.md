# Tcl Proc Bug

This repository demonstrates a subtle error in a Tcl procedure that returns the larger of two numbers. The procedure fails when the input numbers are equal.  The solution provided addresses this shortcoming.

## Bug Description

The `badproc` procedure incorrectly handles the case where the input numbers `a` and `b` are equal. It should return either value in this case but currently returns only one of them. 

## Solution

The solution introduces a more robust implementation that explicitly handles the equality case, ensuring the procedure functions correctly for all input values.