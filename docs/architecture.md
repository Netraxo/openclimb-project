# OpenClimb Architecture

## Overview

OpenClimb is a mobile-first application designed for climbers.

The application focuses on simplicity, offline usability and fast access to climbing information.

---

# Mobile

Framework:
- React Native
- Expo

Language:
- TypeScript

---

# Backend

- Supabase

Services:
- Authentication
- PostgreSQL Database
- Storage
- Realtime

---

# Database

PostgreSQL

Main entities:

- Crags
- Sectors
- Routes
- Users
- Route Ratings
- Community Grades
- Comments
- Approach Tracks

---

# Maps

MapLibre

Reasons:

- Open Source
- Offline support
- Fast rendering
- Vector tiles

---

# Topo

SVG overlays

Reasons:

- Infinite scaling
- Route highlighting
- Interactive routes
- Color-coded difficulty

---

# Offline

SQLite

Cached:

- Maps
- Crags
- Sectors
- Routes
- Topos
- Photos
- Approach Tracks

---

# Images

Format:

WebP

Storage:

Supabase Storage

---

# Authentication

Supabase Auth

Supported:

- Email
- Google
- Apple

---

# Project Structure

app/

assets/

components/

features/

    map/

    crags/

    sectors/

    routes/

    search/

    profile/

    approach/

services/

hooks/

types/

utils/

docs/

---

# Design Principles

The architecture follows the principles defined in:

docs/design-principles.md
