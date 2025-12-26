# MoteLink Protocol

A communication protocol for ultrasonic mote-based brain-computer interfaces (BCI).

## Overview

MoteLink enables reliable, low-latency data transmission between implantable ultrasonic neural motes and external processing units. The protocol is designed for mesh networks of up to 1024 motes, targeting sub-10ms round-trip latency for command signals.

## Goals

- **Robust Communication**: Error-correcting protocol stack tolerant of the challenging in-body RF environment
- **Low Latency**: Real-time responsiveness required for closed-loop BCI applications
- **Scalability**: Support for dense mote deployments across multiple brain regions
- **Power Efficiency**: Minimize energy consumption on battery-constrained implantable devices

## Deliverables

1. Protocol specification document (IEEE-style format)
2. Reference implementation in Rust
3. Simulation environment for protocol testing and validation
4. Performance benchmarks and analysis
5. Technical documentation and integration guide

## Background

This work builds on ultrasonic neural dust research (Seo et al., Berkeley 2016) and aims to standardize the communication layer for next-generation distributed BCI systems.

## Project Structure

- `TERMS.md` - Contractual terms and conditions
- `REPO_GUIDE.md` - How to use this repository
- `submissions/` - Project deliverables and documentation

---

*This project is managed through the [Trustless Business](https://trustless.business) ecosystem.*
