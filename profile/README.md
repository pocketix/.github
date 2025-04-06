# Pocketix Ecosystem

Welcome to the Pocketix Ecosystem — a suite of tools and libraries designed for automating smart home and IoT devices. The Pocketix project includes various components that work together to provide a comprehensive visual programming environment for creating automation scripts, device management, and integration with IoT systems.

## Related Projects
- 🔗 [vpl-for-things](https://github.com/pocketix/vpl-for-things) — WIP version of new editor built in Lit compatible with Pocketix v2 language
- 🔗 [pocketix-react](https://github.com/pocketix/pocketix-react) — React version of the editor
- 🔗 [pocketixng](https://github.com/pocketix/pocketixng) — Angular-based scripting editor for the same ecosystem
- 🔗 [Pocketix Node Interpreter](https://github.com/pocketix/pocketix-node) — Executes automation scripts created with Pocketix tools
- 🔗 [Pocketix Node Core](https://github.com/pocketix/pocketix-node-core) — A simple environment for basic IoT management

## Overview

The Pocketix Ecosystem enables the automation of smart devices through visual programming. With both block- and form-based editors, users can design automation workflows using an intuitive drag-and-drop interface without the need for coding experience. The ecosystem is designed to integrate with smart home devices, IoT sensors, and cloud platforms, enabling powerful automation solutions.

- **pocketix-react**: A React-based visual programming editor for creating smart home automation workflows.
- **pocketixng**: An Angular-based editor for designing automation rules and controlling devices in the IoT ecosystem.
- **Pocketix Node**: A backend module that interprets Pocketix V1 programs and sends commands to devices, designed for simulation and testing.
- **Pocketix Node Core**: A monorepo containing backend services, databases, and frontend applications to support IoT and smart device automation.

## Features

- ✅ Visual programming language editors for smart home and IoT automation
- ✅ Drag-and-drop interface with condition/action configuration
- ✅ Block-based and form-based UI for designing automation workflows
- ✅ Integration with smart devices and extensible architecture
- ✅ Supports the Pocketix v1 language version
- ✅ Backend services for IoT device management, including time-series storage and serverless functions
- ✅ Scalable architecture designed for real-world IoT applications

## Usage
- **pocketix-react** and **pocketixng** offer a user-friendly interface for designing automation rules using visual blocks. You can drag and drop blocks, configure their parameters through forms, and integrate smart home devices into the workflow.
- **Pocketix Node** provides the runtime environment for interpreting automation scripts, executing them in a dry-run mode, and interacting with IoT devices or simulating actions.
- **Pocketix Node Core** houses the backend services and databases that power the entire ecosystem, allowing for scalable and cloud-integrated device management.

## Contributing

We welcome contributions! To get involved:

1. Fork the repository and create a new branch for your feature or fix
2. Follow our code style (checked via ESLint or TSLint)
3. Write tests to ensure your changes don’t break functionality
4. Submit a pull request with a clear description of your changes

## License

All projects in the Pocketix Ecosystem are licensed under the MIT License. See individual project LICENSE files for full details.

## Roadmap

- 📦 Distribution of V1 tools as libraries for integration into other applications.
- 📈 V2 Interpret, Editor and RIoT — new core backend runtime written in Go and offering more robust environment with more capabilities like KPIs.  

## Leadership
- [Petr John](https://github.com/xjohnp00): PhD student and the leader of the Pocketix project. Petr is focused on the development and continuous improvement of the Pocketix ecosystem, primarily in visual programming for IoT and other optimizations.

## Contributors
The Pocketix project has been supported by a variety of contributors and students, including:
- [Lukáš Podvojský](https://github.com/podvojsky) — Responsible for the first iteration of V2 Editor and Language
- [Michal Bureš](https://github.com/MichalBures-OG) — Responsible for the first iteration of RIoT environment (original version available under [RIoT-IS](https://github.com/MichalBures-OG/RIoT-IS))

Their dedication, collaboration, and expertise have helped shape the Pocketix ecosystem into a robust tool for smart home automation and IoT management.

## Mentoring
- [Jiří Hynek](https://github.com/jirka): PhD supervisor at BUT FIT
