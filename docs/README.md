# Getting Started

1. **Fit the module.** Mount a Raspberry Pi Compute Module 5 on the two 100-pin sockets (power off). With a CM5 Lite, the system boots from the microSD slot; with an eMMC CM5, from the on-module eMMC (USB boot mode is described in Test 04).
2. **Prepare the system.** Write Raspberry Pi OS (64-bit) with Raspberry Pi Imager, set user name, password and hostname, and enable SSH. The complete procedure is in section 3 of the [MIPI Camera test guide](../tests/01-mipi-camera/SaturnVex_PCM5_MIPI_Camera_Test_Guide_EN.pdf).
3. **First boot.** Connect Ethernet (RJ1) and 5 V, wait 1–2 minutes and log in from the PC with `ssh <user>@<board-ip>`.
4. **Run the tests.** Each [test project](../tests/README.md) has its own package and guide.

All header I/O is 3.3 V logic. Connect or disconnect cameras, sensors and cables only with the board powered off.

[← Product home](../README.md)
