# IBIS

IBIS is a flexible edge computing infrastructure framework designed to simplify the deployment and management of measurement applications on distributed edge devices. Built as a customization of [CHI@Edge](https://chameleoncloud.org/experiment/chiedge/), IBIS trades granular control for ease of use, making it accessible for researchers and organizations to deploy wide-scale data collection campaigns without extensive technical expertise.

## Overview

The IBIS framework provides a complete infrastructure stack for:
- **Remote application deployment**: Deploy custom measurement and monitoring applications to edge devices on scheduled intervals
- **Centralized device management**: Monitor and manage fleets of edge devices from a unified dashboard
- **Data collection pipeline**: Automated data upload from edge devices to highly available datacenter services
- **Flexible hardware integration**: Support for various peripherals (GPS, cameras, environmental sensors, etc.) to adapt to diverse research objectives
- **Multi-tenant support**: Run multiple independent applications on the same infrastructure

Originally developed to support broadband quality studies through the [FLOTO Center for Broadband Research](floto.cs.uchicago.edu), IBIS's architecture enables researchers to easily adapt the infrastructure for new scientific domains by integrating custom peripherals and measurement applications—from environmental monitoring to agricultural sensing.
