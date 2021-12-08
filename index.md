## Atreyu Keyboard

An unsplit keyboard based on Atreis and Lily58.

![AtreyuKeyboard](https://github.com/climent/atreyu/raw/main/pictures/PXL_20210609_174723137.jpg?raw=true)

Atreyu is a 6x4+5 keys, column-staggered unsplit keyboard based on the Atreis keyboard (itself an unsplit Iris keyboard) with an additional key like the Lily58 keyboard.

Based on [Dekonnection's Atreis keyboard design files](https://github.com/dekonnection/atreis), modified to achieve the same layout of the split Lily58 in a single-piece form-factor.

## Why?

Because the Atreis is the most convenient keyboard to take when on the go, but I need a couple of extra keys, like the Lily58.

## Why this name ?

Because it looks a lot like the Atreis keyboard, but with the Lily58 layout.

## How do I build one ?

I'm [designing a PCB](http://github.com/climent/atreyu-pcb) for it, but it will take some time as I have to learn how to use KiCad, so for now you can download the SVG and get it cut from Ponoko.com or a similar place. The wiring is quite straightforward: rows are independent, and columns are combined together across both sides (columns are connected from outside to inside). You can [check this picture](pictures/atreyu-wired.jpg?raw=true "The wires").

# Firmware

You can find my copy of the keyboard mapping [here.](http://github.com/climent/qmk_firmware/tree/master/keyboards/atreyu/)

I will eventually do a merge request in upstream QMK.
### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
