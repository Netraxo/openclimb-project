# OpenClimb Database

## Status

🚧 Work in Progress

This document describes the database architecture of OpenClimb.

---

# Database Philosophy

The database is designed around the climbing experience.

The rock comes first.

Users, moderators and applications are built around the climbing data.

---

# Core Structure

```text
Region
│
├── Sector
│      ├── Route
│      ├── Topo
│      ├── Photos
│      ├── Warnings
│      ├── History
│      └── Fixed Gear
│
├── Moderators
│
└── Reports
```

---

## Core Entities

- Regions
- Sectors
- Routes
- Topos
- Photos
- Warnings
- Route History
- Fixed Gear History
- Reports
- Users
- Moderators

---

## Design Principles

- Accuracy over quantity
- Community verified
- Rock first. Code second.
- Mobile first
- Open Source
