# IoTServer releases

Windows downloads for IoTServer, an independent Rust industrial connectivity server with a local browser configuration interface and an OPC UA server.

## Download

[Latest release](https://github.com/IoTServerX/releases/releases/latest)

Version 1.0.0 is available for Windows x64:

- [Windows installer](https://github.com/IoTServerX/releases/releases/download/v1.0.0/IoTServer-1.0.0-windows-x64-setup.exe)
- [Portable ZIP](https://github.com/IoTServerX/releases/releases/download/v1.0.0/IoTServer-1.0.0-windows-x64-portable.zip)
- [SHA-256 checksums](https://github.com/IoTServerX/releases/releases/download/v1.0.0/SHA256SUMS.txt)

The installer runs per user and adds Start Menu shortcuts. Open IoTServer, configure a project, apply it, and start the runtime. Closing the browser leaves the host running; use **Stop IoTServer** to close it. Upgrades and uninstall preserve user data.

## Supported adapters

Allen-Bradley Ethernet, Modbus Ethernet, OPC UA Client, ControlLogix Ethernet, Mitsubishi Ethernet, Siemens TCP/IP Ethernet, MQTT Client, and Memory Based.

These adapters implement documented subsets. Full driver coverage, physical PLC interoperability, and protocol certification are not claimed. OPC DA and serial drivers are excluded. Version 1.0.0 uses a local administration interface and runs interactively, not as a Windows service. MQTT TLS/authentication and memory persistence are pending.

Artifacts are unsigned. Detailed capabilities, setup instructions, limitations, dependency licenses, and required MPL dependency sources are included in the downloads.

This public repository contains release documentation and binary downloads. IoTServer application source is maintained separately in a private repository. This project is independent of the referenced device vendors.
