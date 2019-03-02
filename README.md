# OpSy

OpSy is a Real Time Operating System or RTOS for Cortex-M microcontrollers.
It is designed to support Cortex-M3, Cortex-M4, Cortex-M7 and probably Cortex-M33 in the future.

It is entirely written in C++17, and with GCC in mind.
The typical target compiler is ARM GCC, and it has been developed using version 8-2018-q4-major.

The main goal is to make it as easy as possible to use with STM32 targets.

Code documentation is available at https://eznovsas.github.io/OpSy/

# History

This version of OpSy is the third main iteration of the RTOS. I started the very first implementation when working on the Neuron Flybarless unit.
It has proven to be very reliable with hundreds of thousands of flight with no issue.
I did a complete redesign when working on the EzManta project, which required more tasks, more complexity, etc.
Then, over the years, I built a list of things I would like it to do, or do better, or differently, and as we became ST Partner, we considered releasing it open source.
With the projects we are now working on, and the new products coming from ST (both hardware and software, be patient ;) ), it was time to work on this third iteration.

# Current Version

Current Version is in alpha state, first implementation is done but requires a lot of testing before it is usable in production environment.