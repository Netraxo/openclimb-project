# OpenClimb Grade System

## Purpose

This document defines how climbing grades are stored, displayed and searched in OpenClimb.

The goal is to preserve the original route grade while allowing the climbing community to express the current consensus.

---

# Official Grade

Every route has one official grade.

The official grade is assigned by the first ascensionist or published guidebook.

The official grade never changes.

Example:

VI.2

---

# Community Grade

Users can suggest a different grade based on current conditions and climbing consensus.

The community grade never replaces the official grade.

It is displayed below the official grade.

Example:

Official:
VI.2

Community:
VI.2+/3

---

# User Rating

Users can rate a route from 1 to 5 stars.

Example:

★★★★★

This rating reflects route quality, not difficulty.

---

# Supported Grade Systems

OpenClimb is designed to support multiple grading systems.

Supported now:

- Polish

Planned:

- French
- UIAA
- YDS
- British
- Saxon

Users will be able to choose their preferred grading system in application settings.

---

# Internal Storage

Every route stores:

- Official grade
- Community grade
- Internal numeric value

Example:

Official grade:
VI.2

Community grade:
VI.2+/3

Internal value:
6.25

The numeric value is used only for searching, filtering and sorting.

Users never see this value.

---

# Search

Routes can be searched by:

- Exact grade
- Grade range

Examples:

VI.2

VI.2–VI.3

V–VI

VI.3+

Search supports both official and community grades.

---

# Display Rules

Always display:

Route name + Official grade

Below:

Community grade

Below:

User rating

Example:

🏆 Jack Sparrow    VI.2

★★★★☆

Community:
VI.2+/3

---

# Principles

- Official grades are never modified.
- Community grades reflect current consensus.
- User ratings are independent from grades.
- Internal numeric values are hidden from users.
- Search works with official and community grades.

---

## Related Documents

- [Database](database.md)
- [Search](search.md)
- [UI Specification](ui-spec.md)
