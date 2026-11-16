# Vehicle Detection & Classification (Edge AI) Test

**Board:** `SVX-CPU-PCM5-001` · **Module:** Raspberry Pi CM5 · **OS:** Raspberry Pi OS 64-bit

On-device Edge AI: YOLOX detection and MobileNetV2 classification of vehicles (sedan, SUV, bus, truck, motorcycle) on the live camera image, shown in a PC browser.

## Files

- [Demo video (YouTube)](https://youtu.be/zJSzV0Tif1g)
- [Test setup, connections, commands and acceptance guide (PDF)](SaturnVex_PCM5_Vehicle_Classify_Test_Guide_EN.pdf)
- [Test package (ZIP)](PCM5_Vehicle_Classify_Test_SaturnVex.zip?raw=true)

## Run this test

1. Read the PDF guide and prepare the hardware. For a new board, start with the microSD preparation and first boot in the [MIPI Camera guide](../01-mipi-camera/SaturnVex_PCM5_MIPI_Camera_Test_Guide_EN.pdf).
2. Download and extract `PCM5_Vehicle_Classify_Test_SaturnVex.zip` on the PC.
3. Copy the `SVX_PCM5_Vehicle_Classify` folder to the board over SSH (`scp -r`), log in and run the scripts as described in the guide.
4. Verify the results using the PDF acceptance criteria.

SaturnVex files are provided under the BSD-3-Clause license (`LICENSE.txt`). Raspberry Pi OS and the other tools installed on the board keep their own licenses (`NOTICE.txt`). The AI models are downloaded by `01_setup.sh` from their official releases and keep their own licenses.

[← All tests](../README.md) · [← Product home](../../README.md)
