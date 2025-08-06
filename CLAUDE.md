# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Plantastic is a revolutionary Lego®-based smart gardening system that combines physical construction with IoT technology. The project enables urban dwellers to grow plants in customizable Lego®-built containers with automated monitoring and watering systems.

## System Architecture

The project is designed as a multi-component ecosystem:

### Hardware Components
- **Modular Design**: Lego®-compatible physical components including intercepts, base stands, cylinders, joints, vase stands, top covers, vases, steaming cases, camera rails, water pools, and cameras
- **IoT Integration**: Sensors for moisture monitoring and automated watering systems
- **Video Capture**: Built-in time-lapse camera system for growth documentation

### Software Architecture

The system follows a distributed architecture with four main components:

1. **Server Component** (`Software/Server/`)
   - AI-powered plant recognition system
   - Video streaming and growth moment storage
   - Watering schedule database and control system
   - Central data processing and coordination hub

2. **Raspberry Pi Component** (`Software/Raspberry/`)
   - Camera control for automated plant photography
   - Local watering system control and sensor management
   - Edge computing for real-time plant monitoring

3. **Mobile Application** (`Software/MobileApp/`)
   - Real-time plant status monitoring
   - Social media sharing integration
   - Remote system control interface

4. **Web Platform** (`Software/Website/`)
   - Online plant status dashboard
   - Component marketplace for hardware extensions
   - Service subscription management
   - Community features including garden visiting and plant/garden voting system
   - Social sharing and community engagement tools

## Key Features

- **Automated Plant Care**: Sensor-driven watering with plant-specific schedules
- **Growth Documentation**: Time-lapse video capture and sharing
- **Plant Recognition**: AI-powered plant identification (in development)
- **Community Platform**: Social features including garden sharing and voting
- **Modular Hardware**: Expandable Lego®-compatible physical system
- **Cross-Platform Access**: Mobile app and web interface for system control

## Development Notes

- This is an early-stage project with conceptual architecture defined
- No active codebase currently exists - all components are in planning/design phase
- Hardware specifications are in draft concept stage
- Software components are defined but not yet implemented
- Project welcomes contributions to codebase, design, and documentation

## Project Structure

The project follows a comprehensive organizational structure designed for scalability and team collaboration:

```
Plantastic/
├── 01_Project_Management/          # All planning, documentation, and proposals
│   ├── Documentation/              # Architecture docs, requirements, API docs
│   ├── Planning/                   # Roadmaps, phase plans, milestones
│   └── Proposals/
│       └── Business_Proposals/
│           └── Original_Proposal/  # Complete project documentation and proposals
├── 02_Hardware/                    # Electronics, mechanical design, 3D printing
│   ├── Electronics/
│   │   └── Component_Specs/
│   │       └── Hardware_Components/ # Original hardware specifications
│   └── Mechanical/                 # CAD models, 3D printable parts
├── 03_Software/                    # All code and software components
│   ├── Embedded_Systems/           # Raspberry Pi and firmware
│   ├── Backend/                    # Server, APIs, databases
│   ├── Frontend/                   # Mobile apps, web platform
│   └── Original_Software_Specs/    # Original software specifications
├── 04_Botanical_Science/           # Plant knowledge, research, protocols
│   ├── Plant_Database/             # Species info, care protocols
│   └── Expert_Knowledge/
│       └── Knowledge/              # Technical knowledge base
├── 05_Education/                   # Curriculum, learning materials, STEM
│   ├── Curriculum/                 # K-12 programs, STEM modules
│   └── Learning_Materials/
│       └── Video_Content/
│           └── Education/          # Educational content and tutorials
├── 06_Design_Assets/               # UI/UX, branding, marketing materials
├── 07_Testing_Validation/          # All testing activities and results
├── 08_Community_Content/           # User-generated content, guidelines
├── 09_Business_Operations/         # Market research, financials, sales
├── 10_Archive_Legacy/              # Historical files, deprecated content
├── LICENSE                         # Project license
└── README.md                      # Project overview and getting started guide
```

## Development Workflow

The project follows a 4-phase development approach:

**Phase 1 (Months 1-6)**: Foundation & Proof of Concept
- Hardware MVP development and basic software architecture
- Located in: `01_Project_Management/Proposals/Business_Proposals/Original_Proposal/`

**Phase 2 (Months 7-12)**: Enhanced Features & Beta Launch
- AI plant recognition, advanced hardware, beta testing program

**Phase 3 (Months 13-24)**: Market Launch & Scaling
- Production readiness, business model implementation, educational partnerships

**Phase 4 (Months 25-36)**: Advanced Features & Expansion
- Global expansion, advanced IoT integration, product line diversification

### Development Guidelines:

1. **Planning Phase**: Review comprehensive project documentation in `01_Project_Management/`
2. **Architecture Design**: Reference technical specifications in respective numbered folders
3. **Implementation**: Use organized folder structure for component development
4. **Integration**: Components communicate through central server coordination
5. **Documentation**: Maintain documentation in `01_Project_Management/Documentation/`

## Contributing Guidelines

- Fork the repository and contribute to codebase, design, or documentation
- Focus on developing the four main software components (Server, Raspberry, MobileApp, Website)
- Hardware contributions welcome for Lego®-compatible component design
- Community engagement through forums and social sharing features

## Memory Notes

- Memorized key details about Plantastic project architecture and development approach