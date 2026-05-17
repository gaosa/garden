# 🌱 garden

A small public space for things I've made — trips, notes, sketches.

Live at: https://gaosa.github.io/garden/

## Structure

```
garden/
├── index.html              # main landing
├── trips/                  # trip plans (HTML/JS only, no API keys)
│   └── YYYY-MM-<dest>/
│       ├── index.html
│       ├── plans.html      # interactive plan comparison + Leaflet map
│       └── picker.html     # drag-and-drop inventory → day plan
└── README.md
```

## Adding a new trip

1. Create `trips/YYYY-MM-<destination>/` folder
2. Drop in `index.html`, `plans.html`, `picker.html`
3. Update root `index.html` to link to it
4. Commit + push — Pages auto-rebuilds

## Notes on what goes here

- Anything I'd be OK with strangers seeing
- No personal/private content (those stay in private repos)
- Self-contained HTML/CSS/JS only — no build step, no secrets
