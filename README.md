# digital_fishtank

First things first:
This Fishtank runs on processing, in Java mode.

https://processing.org/

https://github.com/processing-js/processing-js



If you haven't been to Khan Academy's https://www.khanacademy.org/computing
section, I highly recommend it.

This project is a development of the Challenge activity, here.
https://www.khanacademy.org/computing/computer-programming/programming-natural-simulations/programming-vectors/pp/project-computational-creatures


The goal is to have as much intricacy of expressiveness (*character*, if you will) of behavior as possible, with the simplest possible sprite.

The Tadpole class has a lot going on inside it which contributes to the complexity of its behavior, but ultimately it's drawn on the canvas as a simple circle and a line for a tail.

For now the only environmental factors influencing any-one's behavior is gravity. It influences the foods.
The tadpoles only real governing forces are
- the foods
- each other

I've imagined the viewport as the pane of a fishtank, but I've also imagined it as a top-down view. If you want to get technical, the latter makes more sense, but only because the foods, when eaten or spoiled, reappear somewhere near the center of the field. So its like a steady rain of delicious red ellipses in varying sizes.

An interesting note is that these particular settings don't scale, because of how the viewport works. I **could** go in an make it so it displays equally well on a (200,200) field as a (2000, 2000)... Or you could.
