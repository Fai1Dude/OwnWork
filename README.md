# 🎨 UX / UI Design Portfolio

This repo collects the **Figma design files** and public prototypes for four
separate projects I built during 2024-25 coursework and freelance work.
There is **no production code here**—only polished design systems, user flows,
and clickable mock-ups ready for hand-off to developers.

| Project | Platforms | What’s in the .fig | Prototype link |
|---------|-----------|-------------------|----------------|
| **JobMatch – Desktop** | Web (1280 px) | 45 screens • job-seeker & employer flows • atomic design system | [Figma prototype ↗](https://www.figma.com/proto/OmLERH3i5h2uRaV45DRN0y/Swe363-Phase-3?node-id=181-6550&scaling=min-zoom) |
| **JobMatch – Mobile** | Mobile (375 px) | 32 screens • bottom-nav • dark/light themes | [Figma prototype ↗](https://www.figma.com/proto/rfUCAFRLrR0NFf1UPavEoE/Mobile-view?node-id=2-9901&scaling=scale-down) |
| **Tutor App (Coursera-style App)** | Mobile | 25 screens • course cards • progress tracker | [Figma prototype ↗](https://www.figma.com/proto/srnKViyEiutQNau0dzqwMA/SWE216?node-id=202-429&scaling=scale-down)|
| **Uni-Tournament Manager** | Mobile | 18 screens • bracket visualiser • admin dashboard | [Figma prototype ↗](https://www.figma.com/proto/3Kmv658HpFOytQDtKhgSIJ/PROJDONE?node-id=0-3&scaling=scale-down) |

> **How to preview locally**  
> Open any `*.fig` file in **Figma Desktop** (or drag-and-drop into the web
> app). All components use Auto-Layout and Variants, so you can inspect
> constraints and export assets at any resolution.

---

## ✨ Highlights

* **Consistent design tokens** – color variables and 8-pt spacing across all
  projects.
* **Responsive grids** – each desktop screen adapts from 1440 px → 1024 px,
  documented in the layout guides.
* **Clickable flows** – every primary user story (sign-up, create listing,
  join tournament, enroll in course) is fully prototyped for user testing.
* **Hand-off ready** – components are named for easy mapping to React /
  Flutter code (`Button/Primary`, `Input/TextField`, `Card/Course`).

---

## Folder structure

designs/

├─ JobMatchDesktopView.fig

├─ JobMatchMobileView.fig

├─ Uni-Tournament-Manager.fig

└─ Mobile Program for tutoring like coursera.fig

ALLS.txt # Figma share links + notes
