# Agri-Sim

<p align="center">
  <img
    width="1513"
    height="786"
    alt="Agri-Sim agricultural greenhouse simulation platform"
    src="https://github.com/user-attachments/assets/d0048aed-5700-428b-8856-f31f769d11ec"
  />
</p>

Agri-Sim is an agricultural embodied-intelligence virtual training platform developed with Unity and ROS 2.

The platform provides virtual agricultural environments, mobile manipulation robots, simulated sensors, and task scenarios for robotics development, training, and evaluation.

## Features

- Agricultural greenhouse simulation
- Mobile manipulation robot
- Navigation and manipulation tasks
- RGB-D camera simulation
- LiDAR and IMU simulation
- Unity–ROS 2 communication
- Embodied-intelligence training and evaluation

## Current Release

The current testing release is **Agri-Sim v0.5.1** for Ubuntu x86_64.

This release includes:

- The latest corrected Agri-Sim project build
- A complete Unity Linux standalone application
- Agricultural greenhouse simulation environments
- Mobile manipulation robot simulation
- Navigation and manipulation task support
- Simulated RGB-D camera, LiDAR and IMU sensors
- Unity–ROS 2 communication support
- Updated installation and execution instructions
- SHA256 checksum for package verification

Version `v0.5.1` is currently distributed as a pre-release for testing and evaluation.

## System Requirements

- Ubuntu 22.04
- x86_64 processor
- Dedicated NVIDIA GPU recommended
- ROS 2 Humble for ROS communication features

## Download

Download the current Ubuntu build from the following page:

[Agri-Sim v0.5.1 – Ubuntu x86_64](https://github.com/tough-titmouse/Agri-Sim/releases/tag/v0.5.1)

Package name:

```text
AgriSim-v0.5.1-Ubuntu-x86_64.tar.gz
```

## Installation

Open a terminal in the directory containing the downloaded package and extract it:

```bash
tar -xzvf AgriSim-v0.5.1-Ubuntu-x86_64.tar.gz
```

Enter the extracted directory:

```bash
cd Agri-sim
```

Add execution permission to the application:

```bash
chmod +x AgriSim-v0.5.1-Ubuntu-x86_64.x86_64
```

## Run

Start Agri-Sim with:

```bash
./AgriSim-v0.5.1-Ubuntu-x86_64.x86_64
```

ROS 2 Humble is required when using the ROS communication features. The standalone simulation can be launched independently when ROS communication is not required.

## File Verification

SHA256:

```text
00D4D322912EC0B2342C1339F378DD2E92B723B61E68258BDE608BFE403952C2
```

Verify the downloaded package with:

```bash
sha256sum AgriSim-v0.5.1-Ubuntu-x86_64.tar.gz
```

The returned value should match the SHA256 checksum shown above.

## Release History

| Version | Platform | Status | Description |
| --- | --- | --- | --- |
| v0.5.1 | Ubuntu 22.04 x86_64 | Pre-release | Updated build with recent fixes and revised documentation |
| v0.5.0 | Ubuntu 22.04 x86_64 | Pre-release | First public Ubuntu build |

See all published versions on the [Releases](https://github.com/tough-titmouse/Agri-Sim/releases) page.

## Feedback and Issues

Agri-Sim is currently under development and evaluation.

If you encounter a problem, please submit a report through [GitHub Issues](https://github.com/tough-titmouse/Agri-Sim/issues). When reporting an issue, please include:

- Ubuntu version
- GPU model and driver version
- ROS 2 version, if applicable
- Steps required to reproduce the problem
- Screenshots or log information, when available

## Project Status

This repository currently provides documentation and downloadable application builds. Additional documentation and project resources may be added in future releases.
