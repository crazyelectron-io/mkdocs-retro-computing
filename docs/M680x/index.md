# Motorola MC680x microprocessor family

Motorola introduced the MC6800 8-bit processor in 1974, in competition with Intel's 8080.
It's instruction set was simple and clean - inspired by the PDP-8 - and it came with a family of associated memory and I/O devices which made it easy to build a complete computer system.

![Motorola MC6800 MPU](assets/MC6800MPU.jpg)

It was also the first microprocessor that could run on a single +5V power supply which greatly simplified the design of a complete system.
Other microprocessors of these early days required -5V, +5V and +12V supplies because of the NMOS technology, but Motorola added a buitin voltage inverter and doubler.
The 6800 was clocked at 1 MHz while an improved version could run at 2 MHz.
This interesting [Wikipedia](https://en.wikipedia.org/wiki/Motorola_6800){:target="_blank"} article describes the history of Motorola and how the 6800 was eventually created.

In 1978 Motorola introduced a greatly improved microprocessor, the [MC6809](https://en.wikipedia.org/wiki/Motorola_6809){:target="_blank"}.
It was an 8-bit processort with a richer instruction set and several 16-bit instructions.

One key diffence between the Motorola and Intel processors was the I/O addressing.
The Intel microprocessors used specific I/O ports seperate from regular memory space while the Motorola 680x microprocessers placed I/O devices in the RAM/ROM memory space and therefor needed no seperate I/O instructions.

# Motorola MC6800 Evaluation Kit II
After having played around with the Elektuur SC/MP II for a while, I was ready for a next step and bought a kit based on the MC6800, consisting of all the parts which had to be soldered on the provided PCB's.
Back then I was a teenager, so I had to safe up for buying this computer which costed the equivalent of around $ 350-400 if I remember correctly.
