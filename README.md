# Oxygen-DMA: Hardware-Backed Stealth Detection

## Overview
This repository contains ongoing research into side-channel analysis for identifying DMA (Direct Memory Access) devices used in adversarial gaming contexts. 

## Key Research Areas
* **Bus Latency Monitoring:** Detecting anomalies in memory access times caused by external PCIe leeching.
* **TLP Header Validation:** Analyzing Transaction Layer Packets for non-standard compliant signatures.
* **IOMMU/VT-d Enforcement:** Investigating bypass techniques for DMAR (DMA Remapping) tables.

## Current Progress
- [x] Initial timing-attack proof of concept.
- [ ] Integration with hypervisor-level memory shadowing.
- [ ] Synthetic jitter injection for device fingerprinting.

## Legal Disclaimer
This project is for educational and security research purposes only.
