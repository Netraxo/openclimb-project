# Sector Screen

## Purpose

The Sector Screen helps climbers quickly choose a climbing route.

This is the most frequently used screen while climbing.

---

## User Goal

Choose a climbing route in the shortest possible time.

---

## Success

The user finds and selects a route within seconds without leaving the topo.

---

# Layout

Header

- Sector name

Hero Image

- Sector photo

Interactive Topo

- Full sector topo
- Routes are selectable

Sector Information

- Number of routes
- Difficulty range
- Maximum height
- Sun exposure
- Approach time

Route List

Each route displays:

- Route name
- Official grade
- Community rating (★★★★★)
- Climbing type
- Number of quickdraws
- Protection character
- Route character

Selecting a route opens the Route Preview Card.

---

# Example

🪨 Sector A

📷 Sector Photo

🧗 Routes: 6

📏 Max height: 10 m

📈 Difficulty: V – VI.3+/4

🧭 East / North

🥾 Approach: 5 min

────────────────────────

🏆 Jack Sparrow      VI.2

★★★★★

Sport

5 quickdraws

🙂 Cautious

Vertical • Arete • Roof

────────────────────────

Blackjack          VI.4

★★★★☆

Sport

6 quickdraws

😬 Demanding

Overhang

---

# Interactive Topo

The topo and the route list are synchronized.

Selecting a route on the topo automatically highlights the corresponding route in the list.

Selecting a route in the list automatically highlights the route on the topo.

Only one route can be selected at a time.

The selected route remains highlighted until another route is selected.

---

# Route Preview Card

Selecting a route does NOT immediately open the Route Screen.

Instead, a bottom sheet appears.

Example:

🏆 Jack Sparrow

VI.2

★★★★★

Sport

8 m

5 quickdraws

🙂 Cautious

Vertical • Arete • Roof

[ Open Route ]

The user can:

- close the card
- select another route
- open the full Route Screen

The topo always remains visible behind the card.

---

# Route Screen

The full Route Screen opens only after selecting:

Open Route

---

# User Flow

Map

↓

Crag

↓

Sector

↓

Select Route

↓

Route Preview Card

↓

Open Route

↓

Route Screen

---

# Design Principles

- Topo is always the primary element.
- The map and topo should never disappear unnecessarily.
- Minimal scrolling.
- Route comparison should be possible without opening multiple screens.
- One tap highlights a route.
- Two taps open the complete route page.
- Keep the interface clean and distraction-free.
