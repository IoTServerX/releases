Data In Motion Enterprise

# IoT Server

Agentic industrial infrastructure for Windows. Connect equipment, organize signals,
and build visual maps with modeling, transformation, simulation and AI-assisted engineering.

## Download

- [Windows installer](https://github.com/IoTServerX/releases/releases/download/v1.3.4/IoTServer-1.3.4-windows-x64-setup.exe)
- [Portable ZIP](https://github.com/IoTServerX/releases/releases/download/v1.3.4/IoTServer-1.3.4-windows-x64-portable.zip)
- [Release notes, checksums and dependency notices](https://github.com/IoTServerX/releases/releases/latest)

Setup offers **Desktop** or **Windows service** mode, both installed in
`C:\Program Files\IoTServer`. The DIME desktop shortcut opens the web UI at
[localhost:5180](http://localhost:5180). In Desktop mode it starts the host if
needed; **Start IoTServer** is also available in the Start Menu. Service mode
starts the host with Windows.

Startup restores the last applied configuration and keeps newer saved edits
pending. Enable **Run on startup** in project properties, then Save and Apply,
to start acquisition and mapping automatically. Older projects need one initial
Apply with this version to establish their checkpoint.

Upgrades automatically stop this installation's host and MCP bridge before
replacing files. Back up your project and security stores before upgrading.

Under **Administration > MCP Server**, download the Claude Desktop extension or
Connect Codex helper to set up tokens and test the connection without editing
configuration files manually.

Without a full license, the runtime is limited to a four-hour process trial.
Use **Administration > Licensing** to obtain the machine ID and activate a license.

Windows binaries are unsigned. Drivers implement documented subsets; hardware
qualification and protocol certification remain incomplete.

[Visit the website](https://iotserverx.com/)
