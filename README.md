# Indoor Asset Manager

An interactive indoor mapping and IT asset management web application for managing office rooms, whiteboards, devices, and personnel.

## 1. Project Overview

Indoor Asset Manager aims to connect indoor spatial information with IT asset management.

The system uses an interactive office floor plan as its main interface. Users can select rooms, view associated devices, manage device information, and track equipment movements between rooms.

The initial prototype will use publicly available or self-created floor plan data and synthetic asset and personnel records.

## 2. Project Objectives

- Visualize office rooms on an interactive floor plan.
- Manage room information and spatial boundaries.
- Register whiteboards and other IT equipment.
- Store and search device MAC addresses.
- Associate employees with rooms and devices.
- Track equipment movements and maintain historical records.
- Explore the integration of GIS technologies with indoor asset management.

## 3. Core Features

### Room Management
- Room ID and room name
- Room type and description
- Room boundaries represented as polygons

### Device Management
- Device ID and device name
- Device type and model
- MAC address
- Current room assignment
- Device movement history

### Personnel Management
- Employee ID
- Employee number
- Employee name
- Room and device associations

### Interactive Indoor Map
- Display an office floor plan
- Select rooms interactively
- Visualize device locations
- Query assets by room

## 4. Technology Stack

| Component | Planned Technology |
|---|---|
| Backend | Python, FastAPI |
| Frontend | HTML, CSS, JavaScript |
| Mapping | Leaflet, SVG |
| Database | SQLite |
| Spatial Data | GeoJSON |
| Version Control | Git, GitHub |

PostGIS may be considered in a future version.

## 5. Project Roadmap

### Phase 1 — Prototype and Data Modeling
- [ ] Create project repository
- [ ] Define database schema
- [ ] Prepare a virtual office floor plan
- [ ] Generate synthetic room, device, and employee data

### Phase 2 — Core Web Application
- [ ] Build FastAPI backend
- [ ] Implement room management
- [ ] Implement device management
- [ ] Implement personnel management
- [ ] Implement device movement records

### Phase 3 — Indoor GIS Integration
- [ ] Convert floor plan into spatial data
- [ ] Define room polygons and device points
- [ ] Build interactive indoor map
- [ ] Implement spatial queries

### Phase 4 — Future Improvements
- [ ] Dashboard and asset statistics
- [ ] Search and filtering
- [ ] User authentication and access control
- [ ] Deployment in an authorized internal environment

## 6. Data and Privacy

The prototype will use synthetic data and publicly available or self-created floor plans.

Real employee information, MAC addresses, and internal company floor plans must not be uploaded to a public repository.

## 7. Project Status

**Status: Planning / Initial Prototype**

This project is currently in the planning and design stage.

The initial goal is to build a functional 2D indoor mapping and asset management prototype before expanding toward a more comprehensive indoor digital twin.

## 8. Long-term Vision

Explore how GIS, indoor mapping, spatial databases, and web technologies can improve IT asset visibility and office space management.
