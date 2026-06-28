# OpenClimb Map System

## Purpose

This document describes how the interactive map works in OpenClimb.

The map is the primary navigation system of the application.

Users should be able to plan an entire climbing day directly from the map.

---

# Core Principle

> The map is the heart of OpenClimb.

The application always starts on the map.

Users do not start from a menu or a list.

---

# Navigation Levels

The map contains four navigation levels.

Area

↓

Crag

↓

Sector

↓

Route

Each zoom level reveals more detailed information.

---

# Area Level

At the lowest zoom level the map displays climbing areas.

Example:

- Góry Kaczawskie
- Rudawy Janowickie
- Jura Krakowsko-Częstochowska

Each marker displays:

- Area name
- Total number of routes

---

# Crag Level

Zooming in displays individual crags.

Each marker displays:

- Crag name
- Number of routes

Selecting a crag opens the Crag page.

---

# Sector Level

Further zooming displays sectors.

Each marker displays:

- Sector name
- Number of routes

Users may open a sector directly from the map without opening the crag page.

---

# Route Level

Selecting a sector opens:

- Sector information
- Topo
- Route list

The map is no longer the primary navigation at this level.

---

# Marker Clustering

Markers merge automatically while zooming out.

Each cluster displays the total number of routes.

Example:

124

24

6

---

# Route Types

Markers display route statistics:

🧗 Sport

🪢 Trad

Future support:

- Boulder
- Indoor
- Ice
- Dry Tooling

---

# Search Integration

Search results are synchronized with the map.

Searching for:

- Area
- Crag
- Sector
- Route

moves the map directly to the correct location.

---

# Filters

Available filters:

- Grade
- Climbing type
- Sun exposure
- Family friendly
- Route height
- Approach time
- User rating
- Classic routes
- Routes with warnings

Filters immediately update the map.

---

# User Experience

The map should require as few interactions as possible.

Users should be able to:

Open the app

↓

Choose an area

↓

Choose a crag

↓

Choose a sector

↓

Start climbing

---

# Design Principles

- Map first.
- Mobile first.
- Simple navigation.
- Minimal number of taps.
- Fast route discovery.
- Clear visual hierarchy.

---

## Related Documents

- [UI Specification](ui-spec.md)
- [Search](search.md)
- [Database](database.md)
