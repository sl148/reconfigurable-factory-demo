# Reconfigurable LEGO Factory — demo

**Live demo:** https://sl148.github.io/reconfigurable-factory-demo/

An interactive 3D demo of a reconfigurable factory: multi-arm robotic workcells assemble LEGO models while mobile manipulators fetch bricks from depots, all planned by a hierarchy of planners — order-to-cell assignment (MILP), multi-robot task planning (pddl-dash), and multi-arm motion planning and validation (comotion).

- **Workcell** — pick a model, place up to four robot arms (or let the planner find the best layout), and watch the planned assembly.
- **Factory** — a recorded session of the full factory: five mobile robots and three workcells under a continuous order stream, with a live-scrolling Gantt chart of the plan.
- **Learn System & Algorithms** — how the planners fit together.

This repository contains only the built static site. Features that need the planners to run (designing your own model, placing live factory orders) are disabled here; the source code will be released later.
