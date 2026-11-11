# AKX PayPoint Print Connector — downloads

The AKX PayPoint Print Connector lets AKX PayPoint print receipts from Chrome or Edge on a
Windows PC to a receipt printer connected by USB or on the shop network. This repository
only hosts the installer; there is no source code here.

## Download

Get the latest installer from **[Releases](../../releases/latest)**:
`AKX-PayPoint-Print-Connector-Setup.exe` (Windows 10/11, 64-bit).

You can also use **Install connector** in AKX PayPoint under
**Settings → Printer Configuration**, which downloads the same file.

## Install

1. Run `AKX-PayPoint-Print-Connector-Setup.exe` and follow the steps. No administrator
   rights are needed.
2. If Windows shows **"Windows protected your PC"**, choose **More info → Run anyway**.
   The installer is not code-signed yet.
3. The connector starts after installing and then every time Windows starts. Its icon
   sits in the system tray.
4. In AKX PayPoint, open **Settings → Printer Configuration**, pick your printer, and
   click **Check connection**.

Supported printers: Volcora POS-80 and Xprinter XP-80T over USB, and any ESC/POS
printer on the network (RAW port 9100).
