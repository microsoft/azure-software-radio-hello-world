# Azure SDR Hello World

In this tutorial we demonstrate the power behind GNU Radio workflows in Azure.  This tutorial was written such that no prior experience with Azure and/or GNU Radio is required to follow along.

In **[Stage 1](stage1/hello_world_stage1.md)** we show how to install GNU Radio and the Azure blocks manually, starting with a fresh Ubuntu 20 VM in Azure.  We then switch over to using our prebuild GNU Radio development VM that lets you skip having to install and configure everything yourself.  As an example GNU Radio application we view the spectrum of the FM radio band, using an RF recording stored in Azure blob storage.

**[Stage 2](stage2/hello_world_stage2.md)** involves demodulating and decoding [ADS-B](https://en.wikipedia.org/wiki/Automatic_Dependent_Surveillance%E2%80%93Broadcast) signals transmitted by commercial aircraft, and send the resulting information into Azure event hub.  We have an RF recording of aircraft in the DC area, but with ~$50 in hardware you can receive and decode signals yourself!

**[Stage 3](stage3/hello_world_stage3.md)** ---something about ATSC---

**[Stage 4](stage4/hello_world_stage4.md)** ---load balancer and DIFI related---

We recommend starting with [Stage 1](stage1/hello_world_stage1.md) and working your way through all stages of this tutorial.