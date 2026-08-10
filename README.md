# FrameCast — PC installer

The PC half of **FrameCast**: the receiver that makes your Android phone show
up on this computer as a webcam, over USB or Wi-Fi.

The app itself comes from Google Play. This repository exists only to host
the PC installer download — the source lives elsewhere; everything shipped
here is plain, readable Python plus the installer script.

## Download

**[Download the latest installer](../../releases/latest)** —
`FrameCast_PC_Setup.zip`

Extract the whole ZIP and double-click **FrameCast Setup**. It is silent: it
prepares a private Python environment, enables OBS's WebSocket and leaves
FrameCast starting with the PC. Full instructions, in Spanish and English,
are inside the ZIP (`README.md`).

## Requirements

- Windows 10/11 with [Python 3.10+](https://www.python.org/downloads/)
  ("Add python.exe to PATH" ticked) and [OBS Studio 28+](https://obsproject.com/)
- Android 8.0+ phone with FrameCast installed from Google Play
