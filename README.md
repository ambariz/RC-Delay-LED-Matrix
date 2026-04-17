# RC Delay LED Matrix

## Overview
An analog LED matrix that creates a smooth "breathing wave" effect using only RC (resistor-capacitor) timing circuits - no microcontrollers, no code.

This project explores how capacitors control time and how voltage propagation can be used to create visual patterns across multiple LEDs.

---

## Demo

![Demo](assets/demo.gif)

Live Demo: https://is.gd/mRAMyU

---

## How It Works

- Each LED is driven by an RC circuit (resistor + capacitor)
- Capacitors charge and discharge gradually → smooth fade in/out
- Different RC values create time delays between LEDs
- Chaining multiple RC stages forms a wave effect

### Key Concepts
- RC Time Constant (τ = R × C)
- Analog signal propagation
- Voltage lag across stages
- Passive timing (no clock, no MCU)

---

## Circuit Idea

- Single LED → basic RC fade
- RC chain → delayed signal across LEDs
- Multiple chains → matrix behavior

---

## Learnings

- RC circuits control timing, not oscillation
- Identical values = synchronized output (boring)
- Variation in components = better visuals
- Analog circuits can mimic "programmable" behavior
