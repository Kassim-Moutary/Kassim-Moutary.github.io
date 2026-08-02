# ARD-001: Blink LED

**Status:** Complete
**Date:** August 2026
**Board:** ELEGOO UNO R3

## Overview
First Arduino project — programming the onboard LED to blink in a
custom double-flash pattern instead of a standard steady blink.

## What I Built
Modified the classic Arduino "Blink" example to create a pattern where
the LED flashes twice quickly (high-low-high-low in rapid succession),
followed by a longer pause before repeating. This required adjusting
the delay() timing values to control how long the LED stays on vs. off.
https://github.com/Kassim-Moutary/Kassim-Moutary.github.io/blob/main/projects/ARD-001/blink_pattern.mp4

## What I Learned
- How digitalWrite() and delay() work together to control timing on a
  microcontroller
- How changing millisecond values in delay() changes the visible
  behavior of the circuit
- Verified the sketch compiled and uploaded successfully (922 bytes,
  2% of program storage)

## Next Steps
- Move the LED off the onboard pin and onto a breadboard with an
  external LED + resistor (Lesson 3)
- Experiment with multiple LEDs and more complex patterns

## Code
See [`blink_pattern.ino`](./blink_pattern.ino)
