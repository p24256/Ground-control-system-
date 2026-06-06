# Ground Control System (GCS) for Multi-Robot Control using ROS 2

## Overview

This project aims to develop a **Ground Control System (GCS)** using **ROS 2** to monitor, control, and coordinate multiple mini robots from a central station.

The GCS acts as a command center that communicates with multiple robots over a network, providing real-time monitoring, telemetry visualization, mission control, and fleet management capabilities.

---

## Objectives

- Control multiple robots from a single interface.
- Monitor robot status and telemetry in real time.
- Send commands and missions to individual robots or groups.
- Visualize robot positions and sensor data.
- Demonstrate ROS 2 multi-robot communication using namespaces.
- Develop a scalable architecture for future autonomous fleet operations.

---

## System Architecture

```text
                Ground Control Station
                         |
                    Wi-Fi Network
                         |
        -----------------------------------
        |                |               |
     Robot 1         Robot 2         Robot 3
