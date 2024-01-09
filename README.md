# ALU_8
_A tiny 8-bit ALU PCB project._

This project is limited to the use of very simple components, including the use of 7400 IC's with only rudementary behaviour. (This also excludes a clock, though I might add one in the future.)

Note this is a first-time learning project, both with respect to [KiCad](https://www.kicad.org/) and PCB design as a whole. Feel free to give tips or insights!

## Design
>_TODO_


---
### Issues
#### Input Switching:
In an attempt to emulate T-flip-flop-like switching behaviour on the input I've opted to use a leader-follower approach. This is quite bulky & resource intensive. Alternative solutions may include:
- Changing the fysical input mechanic; although I'm unaware of a suitable solution
- Adding a clock & using actual T-flip-flops
- Using an analogue solution; of which there seem multiple, though I'm unsure about the design intricacies involved (especially since this seems unorthodox & design-flaw-sensitive).