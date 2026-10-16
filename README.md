# Binary Increment Using a Turing Machine

## Overview
This project demonstrates how a **Turing Machine increments a binary number by one**. The machine is designed using **JFLAP**, with an interactive web frontend built using HTML, CSS, and JavaScript.

## Features
- Binary input validation
- Visual representation of the Turing Machine tape
- Step-by-step simulation
- Automatic execution
- Tape head movement visualization
- Current state and step counter
- Binary increment result
- Upload and parse JFLAP `.jff` files

## Technologies Used
- **JFLAP 6.4** — Turing Machine design
- **HTML5** — Frontend structure
- **CSS3** — Styling
- **JavaScript** — Simulation logic
- **Git and GitHub** — Version control

## How It Works
The Turing Machine uses three states:

| State | Purpose |
|---|---|
| `q0` | Scan right to the end of the binary input |
| `q1` | Perform binary increment with carry |
| `q2` | Accept the final result |

The machine moves right until it reaches a blank symbol, then processes the binary number from right to left.

## Example

**Input:** `1011`

**Output:** `1100`

Other examples:

| Input | Output |
|---|---|
| `0` | `1` |
| `10` | `11` |
| `101` | `110` |
| `1011` | `1100` |

## How to Run
1. Clone or download this repository.
2. Open `index.html` in a browser.
3. Enter a binary number.
4. Click **Start**.
5. Use **Next Step** or **Auto Run** to execute the simulation.
6. View the final output.

## JFLAP Integration
The frontend supports uploading a JFLAP `.jff` file and reading its states and transitions.

**Note:** The current simulation uses JavaScript-defined transitions. Execution directly from the imported JFLAP transitions is a planned improvement.

## Project Information
**Subject:** Theory of Computation

**Project:** Binary Increment Using a Turing Machine

**Purpose:** To demonstrate Turing Machine operations through an interactive simulator.