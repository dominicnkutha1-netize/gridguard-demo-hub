# GridGuard — demo hub

A small launcher for the GridGuard AI demo views: control room, utility view,
technician check-in, resident outage status and a single-transformer simulator.

**The full project is [gridguard](https://github.com/dominicnkutha1-netize/gridguard)** —
this repository is a supporting set of pages, not the main one.

## What is here

| Path | View |
|---|---|
| `index.html` | Launcher (this page) |
| `controlroom/` | Operator fleet overview |
| `eskom/` | Utility-level view |
| `resident/` | Household outage status |
| `key/` | RFID technician check-in |
| `transformer/` | Single transformer unit |

## Running it

No build step. Open `index.html`, or serve the folder:

```bash
python -m http.server 8000
```

## Status

Prototype. All telemetry is simulated in JavaScript; nothing connects to real
hardware or to a utility. Superseded by
[gridguard](https://github.com/dominicnkutha1-netize/gridguard).
