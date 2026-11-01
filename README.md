# GridGuard — Demo Hub

A small launcher for the GridGuard AI demo views: control room, technician, resident,
simulation, and hardware.

**This is a supporting repo.** The main project, with the full write-up and the complete
demo, lives here:

### → [dominicnkutha1-netize/Eskomgrid](https://github.com/dominicnkutha1-netize/Eskomgrid)

## What's here

| Path | View |
|---|---|
| `controlroom/` | Operator fleet overview |
| `eskom/` | Utility-level view |
| `resident/` | Household outage status |
| `key/` | RFID technician check-in |
| `transformer/` | Single transformer unit |
| `hub/` | This launcher page |

Shared logic is in `gg-engine.js`.

## Running

No build step. Clone it, open `index.html`, and click through.

> ⚠️ Prototype. Telemetry is simulated; nothing connects to real hardware or to Eskom.
