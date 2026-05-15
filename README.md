EerieLeap is an open-source data acquisition, processing and monitoring system. It provides a robust platform for reading, processing, and managing sensor data, supporting digital, analog, and CAN Bus data inputs.

## Features

Core features of the system include:

- Real-time sensor data collection and processing
- CAN Bus data collection and streaming
- Data logging
- Custom expressions for sensor value calculation
- Lua script processing for sensor values and CAN messages
- Flexible UI
- Multi device network with many-to-many relationship
- Cross-platform companion app

## Resources

Here's a quick summary of resources to help you find your way around:

* **Documentation**: [EerieLeap Real-Time Documentation](https://github.com/EerieLeap/rt_docs)
* **Wiki**: [EerieLeap Real-Time GitHub wiki](https://github.com/EerieLeap/rt_docs/wiki)
* **CAN Device Management Protocol**: [Documentation](https://github.com/EerieLeap/rt_core/blob/main/src/subsys/cdmp/README.md) for custom CANBus network protocol build for EerieLeap project

## Projects

* **rt_core**: [EerieLeap Real-Time Core](https://github.com/EerieLeap/rt_core) - core common module used by Zephyr RTOS projects
* **rt_daq**: [EerieLeap Real-Time DAQ](https://github.com/EerieLeap/rt_daq) - Zephyr RTOS project for data acquisition and processing device
* **rt_gauge**: [EerieLeap Real-Time DAQ](https://github.com/EerieLeap/rt_gauge) - Zephyr RTOS project for indication device gauge/dashboard