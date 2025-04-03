# Sliver-Linux: Advanced Post-Exploitation Framework

Overview

Sliver-Linux is a powerful post-exploitation framework designed as an open-source alternative to tools like PowerShell Empire and Cobalt Strike. It provides advanced features for penetration testers, focusing on stealth, evasion, and efficient session management.

Features

🔥 Stealth & Evasion

Fully Encrypted C2 Communication – Secure channels to protect command and control interactions.

Bypass AV & EDR – Advanced techniques to evade modern security solutions.

Fileless Execution – Payloads execute directly in memory to avoid detection.


🛠 Advanced Exploitation Capabilities

Modular Framework – Supports multiple modules for executing complex commands.

Multi-Platform Support – Works on Linux, macOS, and Windows.

Interactive Shell – Direct access to compromised systems through C2 channels.


🔗 Networking & C2

Multiple C2 Channels – Supports HTTP/HTTPS, DNS, and MTLS communication.

Auto-Generated Payloads – Easily generate encrypted payloads for various scenarios.

Session Management – Control and manage connected devices efficiently.


Installation

Sliver-Linux can be easily installed on Debian-based distributions (Kali Linux, Parrot OS, etc.) using the .deb package:

sudo dpkg -i sliver-linux.deb
sudo apt-get install -f

Once installed, you can run the tool using:

sliver-server   # Start the C2 server
sliver-client   # Connect to the C2 server

Additional Resources

The package includes a detailed PDF guide that explains how to use the tool effectively. This document is available in the main directory of the tool.

Screenshots & UI

Sliver-Linux features a custom professional icon for an enhanced user experience, along with an interactive CLI for efficient command execution.

Download & Contribute

The project is available on GitHub:
🔗 https://github.com/pashamasr01287654800/sliver-linux

