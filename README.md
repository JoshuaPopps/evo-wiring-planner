# Evo Wiring Planner

A step-by-step planner for building a new 12V wiring harness for a Harley-Davidson Evolution (Evo) Big Twin motorcycle. Answer a few questions about your bike — frame, ignition, controls, electric or kick start, lights, horn — and it builds a complete harness plan: a wire-by-wire list with gauges, colors, fuses and routing notes, a fuse-block layout, a circuit diagram, a frame routing map, and a shopping list.

## How to use it

1. Open `index.html` in any modern browser. There is nothing to install and no server needed; the page is fully static.
2. Work through the questions. Each choice reshapes the plan — the wire list, fuses, diagram, and shopping list all follow what you picked.
3. Read the wire list first, then the fuse layout, then the diagram. Build one circuit at a time, label both ends of every wire before looming, and continuity-test each branch before moving on.
4. Print the plan and keep it with the bike. The shopping list includes fuse counts and estimated prices to take to the parts store.

## What it covers

- Ground-first harness layout: battery-to-engine, engine-to-frame, and dedicated lamp grounds
- Ignition options: stock electronic, Dynatek Dyna 2000i, Dyna S, Crane Hi-4, points conversion, and magneto (ground-to-kill)
- Electric start (relay, solenoid, 4 AWG starter cables) or kick-only
- Headlight (single beam or high/low), tail/brake lamp, turn signals, and horn
- Stock, custom, or minimal handlebar controls
- Frame routing for Softail, Dyna, FXR, Sportster, and rigid frames
- Fuse-block layout, fuse assortment, terminals, loom, and a cost estimate

## Important — read this before wiring

This planner is a **planning reference, not a factory wiring diagram**. It gives you a consistent harness scheme — gauges, colors, fuses, and routing — for a fresh build. It does not replace the service manual for your year and model:

- At every module, regulator, lamp, and stock control connector, identify the terminal **by function from that component's own diagram**, then transition to the planner color after the connector. Component pigtail colors vary by year and maker.
- Confirm coil resistance, regulator requirements, and module settings against the component manufacturer's instructions before connecting the battery.
- Fuse sizes protect the wire, not the accessory. If you change a load, re-check the fuse against the smallest conductor downstream.
- A magneto kill lead grounds to stop the engine. **Never feed it 12V.**
- If anything in the plan conflicts with your bike's factory diagram or a component manual, the factory diagram and the manual win.

## About this project

- Static site: a single `index.html` plus images under `assets/`. No tracking, no accounts, no network calls except the Google Fonts stylesheet.
- The artwork is hand-drawn-style shop illustrations made for this planner.
- No personal data is collected or embedded in this site.
