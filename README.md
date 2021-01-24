WTFpga
======
Two-hour crash course in FPGAs and Verilog using a Digilent Basys 3 board and Xilinx Vivado. This is a fork of [Joe Fitz's 2018 version](https://github.com/securelyfitz/WTFpga) presented at [Teardown 2018](https://www.crowdsupply.com/teardown/portland-2018/updates/sessions#wtfpga).

Purpose
=======
The purpose of this workshop is to jumpstart people new to FPGAs, getting them to the point where they can understand and make minor changes to Verilog designs, and see the results on hardware.

When delivered as a workshop, laptops have Vivado preinstalled and the project preloaded so that attendees can get straight to toggling switches and flashing LEDs.

The scope is intentionally limited to make sure it's doable in a couple hours time, so that attendees don't need to make a huge time commitment to get a hands-on understanding of FPGAs and Verilog.

What's not covered
==================
To keep it simple, I skip over:
1. Toolchain Setup
2. Synchronous Logic
3. IP cores
4. Simulation
5. Testbenches

... and probably lots more things you'll want to be sure to learn more about once you get started.

DIY
===
If you'd like to do this workshop on your own, before you start, you'll need to:
1. Install Xilinx Vivado. The free WebPack version is sufficent: https://www.xilinx.com/products/design-tools/vivado.html
2. Aquire a Diglilent Basys 3 Board. Students qualify for an academic discount: http://digilent.com/basys3
3. Walk through the pdf manual included. `pdfbook --lettterpaper wtfpgamanual.pdf` should prepare it for printing as a booklet if you prefer.

Derivative use
==============
Please use and distribute this material!
