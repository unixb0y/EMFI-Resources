# EMFI Resources
Resources to get started with EMFI, based on my HWIO USA 2023 talk.
<sup>(To-Do: insert link here once talk is online)</sup> 

## Required Components
* Positioning Platform:
  * Either: 3018 CNC (using lead screws)
  * Or: 3D printer / drawing robot (using belts - preferred)

* Delay Generator:
  * FPGA: [Cmod A7-35T](https://digilent.com/shop/cmod-a7-35t-breadboardable-artix-7-fpga-module/)
  * Bitstream: [ChipFail Glitcher :octocat:](https://github.com/unixb0y/chipfail-glitcher)
  * Breakout board: [EMFI Companion :octocat:](https://github.com/unixb0y/EMFI_Companion)
  <img src="https://github.com/unixb0y/EMFI-Resources/assets/6874233/f2d9f499-8554-461f-966d-45b9f316a644" width="25%"/>

* EMFI Pulser:
  * Either: [ChipSHOUTER](https://www.newae.com/chipshouter)
  * Or: [PicoEMP :octocat:](https://github.com/newaetech/chipshouter-picoemp)

## Optional Components (depending on target / needs)
* [Hardware Reset :octocat:](https://github.com/unixb0y) :construction:
<img src="https://github.com/unixb0y/EMFI-Resources/assets/6874233/38e8bda0-f81b-46fc-ad63-7130ab995daa" width="25%"/>

* Debugger:
  * [J-Link](https://www.segger.com/products/debug-probes/j-link/)
  * [Tigard :octocat:](https://github.com/tigard-tools/tigard)
  * [Pico Debug n Dump](https://stacksmashing.gumroad.com/l/picodnd)

## Software
* [EMFIControl :octocat:](https://github.com/unixb0y) for CLI control and scripting of the setup :construction:
* [EMFI scripts :octocat:](https://github.com/unixb0y) for visualization of results and more :construction:

## Work in Progress
* Raspberry Pi Pico based Delay Generator
* 3D printed platform / base for various components
