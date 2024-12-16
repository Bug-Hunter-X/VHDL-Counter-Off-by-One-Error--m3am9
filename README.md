# VHDL Counter Bug Report

This repository contains a buggy VHDL counter and its corrected version. The original counter exhibits unexpected behavior when reaching its maximum count value (15).  The issue lies in the handling of the counter's rollover from 15 back to 0.  The `fixed_counter.vhdl` file demonstrates the solution.  This example highlights the importance of carefully considering edge cases in VHDL designs. 

## Bug Description:

The `buggy_counter.vhdl` shows a counter that may not reset correctly or may exhibit unexpected behavior at its maximum count.

## Solution:

The `fixed_counter.vhdl` provides a corrected implementation addressing the potential issues in the original code.