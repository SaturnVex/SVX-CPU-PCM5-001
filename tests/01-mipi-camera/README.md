# MIPI Camera (MIPI1 / MIPI2) Test

**Board:** `SVX-CPU-PCM5-001` · **Module:** Raspberry Pi CM5 · **OS:** Raspberry Pi OS 64-bit

IMX219 camera on the 22-pin MIPI CSI-2 connectors: sensor detection, live video to a PC browser, Python frame capture, still photo and H.264 recording. The guide also covers microSD preparation and first boot.

## Files

- [Test setup, connections, commands and acceptance guide (PDF)](SaturnVex_PCM5_MIPI_Camera_Test_Guide_EN.pdf)
- [Test package (ZIP)](PCM5_MIPI_Camera_Test_SaturnVex.zip?raw=true)

## Run this test

1. Read the PDF guide and prepare the hardware. For a new board, start with the microSD preparation and first boot in the [MIPI Camera guide](../01-mipi-camera/SaturnVex_PCM5_MIPI_Camera_Test_Guide_EN.pdf).
2. Download and extract `PCM5_MIPI_Camera_Test_SaturnVex.zip` on the PC.
3. Copy the `SVX_PCM5_MIPI_Camera_Test` folder to the board over SSH (`scp -r`), log in and run the scripts as described in the guide.
4. Verify the results using the PDF acceptance criteria.

SaturnVex files are provided under the BSD-3-Clause license (`LICENSE.txt`). Raspberry Pi OS and the other tools installed on the board keep their own licenses (`NOTICE.txt`).

[← All tests](../README.md) · [← Product home](../../README.md)
