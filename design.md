# The Komorebi Design Philosophy

### *Coding in Bioluminescence*

## 1. Executive Summary

**Komorebi** (Japanese: *Sunlight filtering through trees*) is a JetBrains IDE theme designed for the modern developer who values cognitive sustainability. It rejects the harsh, high-contrast norms of traditional "Dark Modes" in favor of a **soft, organic, and bioluminescent aesthetic**.

The primary goal is **Joyful Efficiency**: reducing eye strain during long sessions while using color theory to trigger positive cognitive responses. It is built from the ground up to be **WCAG AAA compliant** and **Deuteranopia/Protanopia friendly**.

---

## 2. The Core Concept: "The Digital Forest"

Most IDE themes are either "Industrial" (Grays and Blues) or "Neon" (High contrast Black and Brights). Komorebi takes a third path: **Organic.**

The interface mimics a walk through a deep forest at twilight.

* **The Background** is not a void; it is a deep, warm charcoal (the forest floor).
* **The Code** is not just text; it is the bioluminescent flora that guides the path.

This metaphor dictates every design choice. We are moving away from "looking at a screen" to "looking into a space."

---

## 3. Accessible by Design (The "Safety" Layer)

Accessibility is often treated as a post-processing filter. In Komorebi, it is the foundation.

### A. The "No-Conflict" Spectrum

Red and Green are the standard indicators for "Stop" and "Go," but they are invisible to 8% of the male population. Komorebi shifts the spectrum:

* **Errors are not Red; they are Magenta/Coral.** This maintains the "alert" signal but moves it out of the confusion zone for protanopia.
* **Success is not Green; it is Mint/Teal.** By adding blue into the green, we create a distinct hue that separates clearly from red/brown.

### B. Double-Coding

We adhere to the strict rule of **Double-Coding**: Information is never conveyed by color alone.

* *Bad:* A red filename indicates an error.
* *Komorebi:* A Coral filename **plus** a wavy underline indicates an error.
* *Bad:* A grey button is disabled.
* *Komorebi:* A low-opacity button **plus** a "not-allowed" cursor indicates disabled state.

---

## 4. Color Theory & Cognitive Load

We use color to manage the developer's dopamine and cortisol levels.

### The "Halation" Problem

Pure white text (`#FFFFFF`) on pure black (`#000000`) causes *halation*—a vibrating visual effect that tires the eyes.

* **The Komorebi Fix:** We use off-whites (`#A6ACCD`) and "Deep Forest" grays (`#1A1C20`). This lowers the contrast ratio just enough to stop the vibration while staying crisp.

### Semantic Joy

We map colors to the emotional weight of the code logic:

* **Keywords (Sakura Pink):** The logic structure. Pink is playful but authoritative. It makes writing logic feel creative rather than administrative.
* **Strings (Golden Hour):** The content. Gold is warm and readable, encouraging the developer to write clear text.
* **Variables (Glacier Blue):** The data. Blue is cool, liquid, and flows through the code.

---

## 5. The Modern Aesthetic (2025+ Trends)

To spark joy, the UI must feel current.

### Soft Depth vs. Flat Design

Complete flatness is fatiguing because the brain struggles to distinguish layers. Komorebi uses **Soft Depth**:

* Sidebar backgrounds are slightly darker than the editor.
* Active tabs don't just change color; they lift slightly.
* This creates a sense of physical space, making the IDE feel like a tactical tool.

### Typography

We prioritize fonts with **High X-Heights** (like JetBrains Mono). This allows code to be legible at smaller sizes, letting developers see more context without squinting.

---

## 6. Technical Palette Reference

### Base Environment

| Element | Hex | Rationale |
| --- | --- | --- |
| **Canvas** | `#1A1C20` | **Deep Forest.** Warm charcoal. Absorbs light, reduces glare. |
| **Chrome** | `#121417` | **Soft Shadow.** Anchors the UI visual hierarchy. |
| **Text** | `#A6ACCD` | **Moonlight.** A cool grey-white that pops without burning. |

### Syntax Accents (The "Joy" Layer)

| Role | Hex | Name | Rationale |
| --- | --- | --- | --- |
| **Methods** | `#C792EA` | **Electric Lavender** | A creative, magical color for the "actions" of code. |
| **Classes** | `#7FD694` | **Mint Leaf** | A safe green. Represents structure and growth. |
| **Values** | `#F78C6C` | **Sunset Orange** | High visibility for numbers and constants. |

---

## 7. Summary

Komorebi is not just a theme; it is an opinion on how software development should *feel*. It asserts that code is clear, the environment is calm, and the tools are inclusive. It turns the IDE from a cockpit into a sanctuary.

---

### Next Step

Since you have the philosophy and the system, would you like me to design a **logo/icon concept** for "Komorebi" that you can use for the plugin file?