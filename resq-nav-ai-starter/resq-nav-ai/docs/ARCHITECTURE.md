# RESQ-NAV AI — System Architecture

## Overview

RESQ-NAV AI consists of five major layers.

### 1. Perception Layer
Processes camera and sensor information.

### 2. Environment Intelligence Layer
Maintains the disaster environment and risk map.

### 3. Decision Layer
Uses BFS, A* and risk-aware planning.

### 4. AI Copilot Layer
Uses an LLM to explain mission state and recommendations.

### 5. Human Interface
Provides the rescue operator with a command dashboard.

## Architecture

```text
Camera / Sensors
        ↓
AI Perception
        ↓
Environment Map
        ↓
Risk Engine
        ↓
BFS / A*
        ↓
Mission Planner
        ↓
AI Rescue Copilot
        ↓
Human Operator
```
