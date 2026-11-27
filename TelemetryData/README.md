# Telemetry Data

**English** | [Chinese](README.zh-CN.md)

Spacecraft and payload telemetry, including measurements from in-orbit computing experiments.

## SatelliteCOTS：[ACM MobiCom 2024 · BUPT-1 In-Orbit Computing Dataset](https://github.com/OPEN-TianSuan/MobiCom24-SatelliteCOTS)

The SatelliteCOTS dataset contains spacecraft telemetry from the BUPT-1 CubeSat and measurements from computing workloads run in orbit on the Atlas 200 DK and Raspberry Pi 4B. It covers temperature changes during sunlight and eclipse, solar power generation, and onboard power consumption.

The repository provides a consolidated telemetry CSV, per-experiment datasets, and Python scripts for data processing and figure reproduction.

The dataset includes **10,117,299 spacecraft telemetry records** spanning March 22 to July 24, 2023. The telemetry tracks solar power, battery charging and discharging, and payload power draw. Experiment data also supports comparisons between ground and in-orbit runs and across workloads and power settings.

The dataset covers ten measurement topics across payload temperature, spacecraft power, and the energy efficiency of in-orbit computing.

| Item | Measurements |
| --- | --- |
| Temperature overview | Surface temperatures with and without computing workloads |
| Temperature and power | Temperature and power under different CPU, NPU, and power settings |
| Payload overheating | Overheating during Atlas and Raspberry Pi inference, in orbit and on the ground |
| Heating rate | Heating rates under different power and workload conditions |
| Sunlight and eclipse | Payload temperatures during sunlight and eclipse |
| Power overview | Solar power generation and onboard power draw with and without computing workloads |
| Single-orbit power and battery cycling | Power over a single orbit and battery charge/discharge curves |
| Long-term energy trends | Solar energy generation and onboard energy use over two weeks |
| Available energy | Solar energy generation and energy use over matched time windows |
| Computing energy efficiency | Ground and in-orbit runs for inference, image classification, and JPEG encoding |

[Dataset and reproduction scripts](https://github.com/OPEN-TianSuan/MobiCom24-SatelliteCOTS)
