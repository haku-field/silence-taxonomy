# Boundary with gesture-kernel

This document defines the boundary between **silence-taxonomy**
and **gesture-kernel**.

---

## Explicit Non-Redefinition

gesture-kernel defines:

- Micro-behaviors
- Timing, restraint, and acknowledgment gestures
- How responses may occur

silence-taxonomy:

- Does not redefine gestures
- Does not assign meaning to gestures
- Does not introduce new gesture semantics

---

## Reference Limitation

silence-taxonomy may:

- Reference gesture-kernel terminology
- Confirm alignment of meaning

silence-taxonomy must not:

- Reinterpret gesture intent
- Convert gestures into silence categories
- Treat silence as a gesture

---

## Hard Boundary

Silence is **not** a gesture.
Gestures are **not** silence.

Any implementation that merges the two
has crossed this boundary.
