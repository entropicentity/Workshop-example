<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

It takes inputs 0-2 and does either a 3 input OR or a 3 input AND operation, returning the output to the output pin. When the Config pin is high, it functions as an AND gate, and when the Config pin is Low, it functions as an OR gate.

## How to test

Connect the three inputs and config pin to configurable digital inputs. Connect the output to an LED or other electronic component that indicates the status of the output signal.

## External hardware

Any output that takes either a High or Low Signal, like an LED. Some way to generate 4 digital signals, either buttons and resistors, or a devboard.
