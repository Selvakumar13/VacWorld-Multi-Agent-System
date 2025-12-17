# VacWorld – Multi-Agent Coordination with ASTRA

This project implements **VacWorld**, a 2D grid-based environment populated by autonomous VacBots, using the **ASTRA agent programming language** and **Java (Maven)**.

The system demonstrates how multiple agents perceive their local environment, reason about tasks, plan movement, and coordinate with each other to clean dust efficiently across the grid.

## Key Features
- Reactive and proactive agent behaviours
- Local perception and belief-based decision making
- Route planning and navigation
- Leader–Follower coordination for collaborative cleaning
- Clean Maven project structure with reproducible builds

## Technologies Used
- ASTRA Agent Programming Language
- Java + Maven
- EIS VacWorld environment

## Project Structure
This repository follows the lab structure where each part represents increasing agent intelligence:
- **Part 1** – Environment setup and agent initialization
- **Part 2** – Reactive cleaning behaviours
- **Part 3** – Proactive route planning
- **Part 4** – Collaborative leader–follower coordination
- **Part 5** – Fully coordinated system that reliably cleans the entire grid

## Build
```bash
mvn clean package
