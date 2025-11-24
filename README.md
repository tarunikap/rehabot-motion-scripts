# REHABOT – RCFS / MuJoCo Motion & Task Scripts (Work in Progress)

This repository contains work-in-progress scripts I am developing as part of my ongoing contribution to the REHABOT project at Idiap. While REHABOT itself focuses on
In massage-like physical human–robot interaction, the scripts are primarily focused on the simulation and Interface side, primarily on the RCFS framework and MuJoCo.

The goal of this code is to organise and test motion patterns and task logic in a simulated setting before they are used in more complete pipelines.

## What this repo includes

Only my own scripts are included here (no internal project code or data is included). They currently cover:

- Loading and handling trajectory / waypoint-style motion data
- Parsing and structuring motions into task-relevant segments (e.g., stroke-like patterns)
- Utilities for interfacing with RCFS / MuJoCo-style setups
- Work-in-progress logic related to soft-start behaviour and preparing motions for massage-type interaction scenarios

These files are primarily for experimentation and do not represent a finished controller or full REHABOT implementation.

## Project context

REHABOT is aimed at safe, compliant interaction for tasks such as massage, where motion must be smooth, structured, and responsive. My work focuses on simulation-specifically, how motions are represented, parsed, and organized so that they can later be utilized by control and interaction frameworks (e.g., through RCFS/MuJoCo).

## Notes

- No experimental data is shared.
- No internal Idiap or REHABOT project code is included.
- All files are simplified or personal versions of scripts I am actively developing and testing in simulation.
