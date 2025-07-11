# SMT2020 AnyLogic Template

> **Work in Progress**

## Overview

The **SMT AnyLogic Template** provides a simulation template for the **Semiconductor Manufacturing Testbed 2020 (SMT 2020)**. Developed using [AnyLogic](https://www.anylogic.com/) and PostgreSQL, this template is designed to accelerate the development, validation, and execution of discrete-event simulation (DES) models for semiconductor manufacturing environments.

The modular and parameterized structure of the template enables rapid adaptation to diverse production scenarios and supports both high-level strategic planning and detailed operational analysis.

## Features

- **Modular Architecture**: Reusable and configurable components representing common manufacturing units such as lots, wafers, toolgroups, tools, and machine failures.
- **Parameterization**: Easily adjust production rates, machine settings, and flows to match specific scenarios.
- **Data Integration Layer**: Supports seamless batch or real-time data integration with production databases via PostgreSQL.
- **Dynamic Initialization**: Initialization driven by database tables to configure toolgroups, lots, recipes, and more.
- **Advanced Tool Management**:
  - Agent-based modeling of toolgroups and tools
  - Pre-batching logic at toolgroup level
  - Dynamic dispatching, ranking, sampling, and reworking
  - Support for lot-to-lens dedication, setup constraints, and preventive maintenance

## Installation

To use the template, follow these steps:

1. **Install AnyLogic** (compatible version required – see [AnyLogic.com](https://www.anylogic.com/) for installation instructions).
2. **Set up PostgreSQL**:
   - Install PostgreSQL locally or on a server.
   - Create the required schema and load data from the `/data` directory.
3. **Clone this repository**:
   ```bash
   git clone https://github.com/mdlnlss/smt-anylogic-template.git
4. **Open the simulation model in AnyLogic** and configure database credentials and runtime settings in the simulation.csv as needed.

## Usage
> Note: Detailed usage instructions and code examples are not yet available. Future versions will include usage guides and illustrative scenarios.

## Technologies
- **Simulation Engine**: AnyLogic
- **Database**: PostgreSQL

## Developer/Maintainer
Madlene Leißau, madlene.leissau@fh-zwickau.de
