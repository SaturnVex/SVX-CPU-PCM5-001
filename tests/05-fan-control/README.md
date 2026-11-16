# CPU Fan Control Test

**Board:** `SVX-CPU-PCM5-001` · **Module:** Raspberry Pi CM5 · **OS:** Raspberry Pi OS 64-bit

Fan connector FAN1 driven by the CM5 Fan_PWM signal: manual check, temperature control with hysteresis and a systemd service.

## Files

- [Test setup, connections, commands and acceptance guide (PDF)](SaturnVex_PCM5_Fan_Control_Test_Guide_EN.pdf)
- [Test package (ZIP)](PCM5_Fan_Control_Test_SaturnVex.zip?raw=true)

## Run this test

1. Read the PDF guide and prepare the hardware. For a new board, start with the microSD preparation and first boot in the [MIPI Camera guide](../01-mipi-camera/SaturnVex_PCM5_MIPI_Camera_Test_Guide_EN.pdf).
2. Download and extract `PCM5_Fan_Control_Test_SaturnVex.zip` on the PC.
3. Copy the `SVX_PCM5_Fan_Control` folder to the board over SSH (`scp -r`), log in and run the scripts as described in the guide.
4. Verify the results using the PDF acceptance criteria.

SaturnVex files are provided under the BSD-3-Clause license (`LICENSE.txt`). Raspberry Pi OS and the other tools installed on the board keep their own licenses (`NOTICE.txt`).

[← All tests](../README.md) · [← Product home](../../README.md)
