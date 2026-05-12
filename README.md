# ConstraintFlow

AI-Powered Dynamic Timetable Optimization & Auto-Rescheduling Engine

---

## Overview

ConstraintFlow is an intelligent scheduling system that generates optimized academic timetables using:

- Natural Language Constraints
- Constraint Programming
- Dynamic Rescheduling
- Human-Aware Optimization
- Historical Fairness Memory
- Stability-Preserving Scheduling

Users can provide constraints in normal human language, and the system converts them into machine-understandable optimization rules.

Example:
- "No AI lab after 3 PM"
- "Dr Rao unavailable on Fridays"
- "Avoid consecutive hard subjects"

---

# Features

## AI Constraint Parsing
- Natural language constraint understanding
- Ambiguity detection
- Interactive clarification

## Optimization Engine
- Constraint Satisfaction Problem (CSP)
- Google OR-Tools CP-SAT optimization
- Priority-based constraint relaxation

## Dynamic Rescheduling
- Localized timetable updates
- Stability-preserving modifications
- Smart substitute allocation

## Human-Aware Scheduling
- Historical workload memory
- Fairness balancing
- Behavioral optimization

## Validation Engine
- Conflict detection
- Dependency analysis
- Duplicate detection
- Feasibility checking

---

# Tech Stack

## Frontend
- React
- Vite
- Tailwind CSS

## Backend
- FastAPI
- PostgreSQL
- SQLAlchemy

## AI & Optimization
- Google OR-Tools
- SpaCy
- RapidFuzz

---

# Project Structure

```bash
ConstraintFlow/
│
├── client/
├── server/
├── docs/
├── deployment/
├── datasets/
└── README.md
