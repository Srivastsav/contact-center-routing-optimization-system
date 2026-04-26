# System Architecture

## Overview
The routing system is designed to intake customer interactions and route them based on predefined workflow logic using queues, skills, and decision rules.

## Layers

### 1. Interaction Intake
- Call / Chat entry points

### 2. Routing Engine
- Decision logic
- Skill-based matching
- Data table lookups

### 3. Queue Management
- Queue selection
- Load balancing

### 4. SLA Monitoring
- Tracks response time
- Ensures compliance

### 5. Testing Layer
- Sandbox validation
- Flow testing before deployment
