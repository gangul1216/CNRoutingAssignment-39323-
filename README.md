# Computer Networks - Routing Assignment

This repository contains the practical deliverables for the Computer Networks routing assignment. The project demonstrates basic router configuration, static routing, and dynamic routing protocols (RIPv2 and EIGRP) using Cisco Packet Tracer.

## Student Details
* **Student Name:** DGS Wassana
* **Student ID:** 39323
* **Submission Date:** June 15, 2026

---

## Repository Contents

This repository includes the following files:
1. **`CNRoutingAssignment_Static.pkt`** - Packet Tracer file for Task 1 & Task 2 (Basic configuration & Static Routing).
2. **`CNRoutingAssignment_RIP.pkt`** - Packet Tracer file for Task 3: Part A (RIPv2 Dynamic Routing).
3. **`CNRoutingAssignment_EIGRP.pkt`** - Packet Tracer file for Task 3: Part B (EIGRP Dynamic Routing).
4. **`Routing_Assignment_Report.pdf`** - Complete documentation including configuration commands, network topologies, routing tables, and connectivity test results.

---

## Project Tasks Overview

### Task 1: Basic Router Configuration
* Configured the custom hostname `KandyNSBM_39323`.
* Secured console line access using password authentication (Password: `NSBM`).

### Task 2: Static Routing Configuration
* Set up an interconnected network involving three routers: `BusinessRouter`, `ComputingRouter`, and `ScienceRouter`.
* Configured static routes (`ip route`) to ensure full end-to-end communication across all local subnets with 0% packet loss.

### Task 3: Dynamic Routing Protocols
* **Part A (RIPv2):** Configured Classless Routing Information Protocol (RIP version 2) across Kandy, Colombo, and Galle routers. Disallowed auto-summarization to maintain subnet accuracy.
* **Part B (EIGRP):** Completely removed the RIP processes and implemented Enhanced Interior Gateway Routing Protocol (EIGRP) with Autonomous System `1`, achieving fast network convergence.

---

## How to Verify and Run
1. Download and install **Cisco Packet Tracer**.
2. Clone or download the `.pkt` files from this repository.
3. Open any of the `.pkt` files to inspect the device topologies and running configurations.
4. Use the Command Prompt on any end-user PC within the simulation to test connectivity using the `ping` command (e.g., pinging from Network A to Network C).
