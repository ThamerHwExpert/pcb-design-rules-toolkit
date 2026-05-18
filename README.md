# PCB Design Rules Toolkit

![Status](https://img.shields.io/badge/status-in%20progress-orange)
![Focus](https://img.shields.io/badge/focus-PCB%20Design%20Rules-blue)
![Tool](https://img.shields.io/badge/tool-Altium%20Designer-green)

## Overview

The **PCB Design Rules Toolkit** is a public engineering resource for building clean, structured, and manufacturable PCB design rules.

It focuses on how to organize constraints, net classes, clearances, trace widths, via rules, power rules, high-speed rules, and manufacturing checks before starting PCB layout.

This repository is designed for PCB designers, embedded hardware engineers, students, and engineers using Altium Designer or similar EDA tools.

---

## Purpose

A PCB can pass basic ERC/DRC checks and still fail in real hardware because the rule system was weak, incomplete, or not connected to manufacturing and signal integrity needs.

This toolkit helps define PCB constraints in a structured way before layout.

---

## Main Topics

- PCB rule architecture
- Net class organization
- Clearance rules
- Trace width and via rules
- Power net rules
- High-speed signal rules
- Differential pair rules
- Solder mask and manufacturing rules
- PCB release checklist

---

## Repository Structure

```text
pcb-design-rules-toolkit/
├── README.md
├── docs/
│   └── 01_rule_architecture.md
└── templates/
    └── design_rules_checklist.md
