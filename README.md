# Unexpected Output in setTimeout Loop

This repository demonstrates a common JavaScript closure issue that occurs when using `setTimeout` within a loop.  The problem arises because the variable `i` is not captured correctly for each iteration of the loop.  The solution involves using an immediately invoked function expression (IIFE) to create a separate scope for each iteration.