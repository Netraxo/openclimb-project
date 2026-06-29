# OpenClimb Architecture 

## Purpose

This document describes the technical architecture of OpenClimb.

The goal is to keep the application simple, scalable and easy to maintain.

---

# Mobile

Framework

- React Native
- Expo

Language

- TypeScript

Reason

One codebase for Android and iOS with excellent community support.

---

# Backend

Platform

- Supabase

Services

- PostgreSQL Database
- Authentication
- Storage
- Realtime API

Reason

Simple architecture with minimal backend maintenance.

---

# Maps

Engine

- MapLibre

Reason

- Open Source
- Offline support
- High performance
- Vector maps

---

# Database

Engine

- PostgreSQL

Main Entities

- Crags
- Sectors
- Routes
- Users
- Route Ratings
- Community Grades
- Comments
- Approach Tracks

---

# Topo

Format

SVG

Reason

- Infinite scaling
- Interactive routes
- Route highlighting
- Difficulty colors

---

# Images

Storage

Supabase Storage

Format

WebP

---

# Offline

Local database

SQLite

Cached data

- Maps
- Crags
- Sectors
- Routes
- Photos
- Topos
- Approach Tracks

---

# Authentication

Supabase Auth

Providers

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

# Principles

The architecture follows the rules defined in:

docs/design-principles.md
