# Part 1: General presentation
Hello, welcome to a new lab about yet another architecture.
Today, we will talk about a peculiar one in the sense that it's not a real-world architecture, it's not implemented on hardware, because it's actually a video game.
The Game is called TIS-100 and is developped and published by [Zachtronics](http://www.zachtronics.com/tis-100/). Everything you need is available on the UV, but if you like the game, I encourage you to support them on GoG.

Now, what is particular about this architecture?
As we will see together, it's composed of *nodes* communicating with each other and very limited in their available data and program memory.

The aim of your assignment is to solve two custom levels, as you will read in the handout.
And to do so, you will need the documentation of the TIS-100.
Let's take a quick look at it, but bear in mind that one of the aim of this session is for you for you to able able to develop some agility concerning the unknown.
When confronted with a new architecture, a new language or a new piece of technology, how do you react? How do you organize your time efficiently to produce the desired results in a short matter of time?

So, the documentation goes over some general aspects of the TIS-100 before detailing the architecture first, then the instruction set. We'll look into the former when we'll play around with the game itself a bit later.

The instruction set is quite limited, but is more than enough to handle your tasks.
It's somewhat similar to the assembly code you wrote during the RISC labs, **but** it's not the same, you can only use instructions presented in the documentation.
We can classify the different kind of instructions as follows:

- Doing nothing: NOP (which can be usefull to synchronize or delay nodes)
- Moving data round: MOV
- Memory management: SWP and SAV
- Arithmetic operations: ADD, SUB and NEG
- Jumping: JMP, JEZ, JNZ, JGZ and JRO
[Don't say the name of the instructions out loud, write them on the screen].

But let's take a look at the game itself to better understand how to use them.

Please refer to the handout in order to know how to load the custom specifications (that is *exercises*) and let's solve the first puzzle together.

[...]