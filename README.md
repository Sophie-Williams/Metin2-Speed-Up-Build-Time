# Metin2-Speed-Up-Build-Time
**Created by blackdragonx61**

For this tutorial, your PC must supports **virtualization technology.**

I tested in this machine: https://github.com/blackdragonx61/Metin2-Update-C-Status

**FreeBSD 12 + Clang-9 + 2 GB Ram:**

Benchmark:

**Game: 2 min.**

**DB: 26 sec.**

Let's start:

1- **Enable virtualization technology(SVM Mode). I enabled at bios. But you can do this whit different ways:**
https://www.wikihow.tech/Enable-Hardware-Virtualization
[![Watch the video](https://img.youtube.com/vi/7J42Y_iE8bs/maxresdefault.jpg)](https://www.youtube.com/watch?v=7J42Y_iE8bs) 

2- **Enable VT at VirtualBox:**
<img src="https://i.ibb.co/zhMQCBq/tempsnip.png" />

3- **Enable I/O APIC at VirtualBox:**
<img src="https://i.ibb.co/M2JxPPv/sdg.png" />

4- **Change Processor setting. Before check your CPU Core Count:**

<img src="https://i.ibb.co/0JnFncg/ryzen-3-1200.jpg" />

<img src="https://i.ibb.co/BLKMcDZ/5312.png" />

Usage:
**gmake -j(core+1)**

**Example I have 4 cores: gmake -j5**
