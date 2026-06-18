# Advanced Modelling - IHTC 2024 Project

This repository contains the code for the Advanced Modelling and Optimization group project on the Integrated Healthcare Timetabling Competition 2024.

## Project Goal

The goal is to generate feasible schedules for IHTC-2024 instances, including:

- patient admission days
- room assignments
- operating theater assignments
- nurse-to-room assignments

The generated solutions must satisfy all hard constraints and should minimize the weighted soft-constraint cost.

## Repository Structure

```text
src/
  main.py
  parser.py
  constructive.py
  nurse_assignment.py
  solution_writer.py
  validator_runner.py

data/
  instances/

solutions/

results/
  summary.csv
