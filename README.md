# Sample Demo

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A ready-to-use VS Code Dev Container template for Java development, pre-configured with Java 17, a desktop environment, and VNC access for GUI-based applications.

## Overview

This repository provides a development container configuration that spins up a fully equipped Java development environment using VS Code Dev Containers (formerly Codespaces). It includes a lightweight desktop environment accessible via VNC, making it ideal for developing and testing Java GUI applications directly from your browser or VS Code.

## Features

- **Java 17 (Zulu FX)** — Pre-installed JDK with JavaFX support via SDKMAN
- **VNC Desktop** — Built-in lightweight desktop environment accessible on port 6080
- **Dev Container Ready** — One-click setup with VS Code Dev Containers or GitHub Codespaces
- **Ubuntu Base** — Built on the official Microsoft VS Code Dev Container base image

## Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running
- Alternatively, a [GitHub Codespaces](https://github.com/features/codespaces) account

## Getting Started

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/danielcregg/sample-demo.git
   cd sample-demo
   ```

2. Open the project in VS Code:

   ```bash
   code .
   ```

3. When prompted, click **"Reopen in Container"** to build and launch the dev container.

### Usage

Once the container is running:

- The Java 17 JDK is available on the system path
- A VNC desktop is accessible at `http://localhost:6080` in your browser
- Write and run Java applications, including GUI applications, directly within the container

## Tech Stack

- **Java 17 (Zulu FX)** — JDK with JavaFX support
- **Docker** — Containerized development environment
- **VS Code Dev Containers** — Reproducible development setup
- **noVNC** — Browser-based VNC client for desktop access

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
