# Altoids MP3

**Revision 1 · Working prototype · Enclosure still to come**

A DIY MP3 player built around an Adafruit KB2040 and a DFPlayer Mini, with a small I²C display, four directional buttons, stereo audio output, and a rechargeable battery.

The hardware and software are about **90% complete**. This is my first revision: a hand-wired prototype on a Perma-Proto board. **I haven't made the shell yet.** I'm documenting the build as it stands, and I hope to release custom PCB designs and 3D printable enclosure files in a later revision.

<p align="center">
  <img src="docs/images/prototype-powered.jpg" alt="Revision 1 prototype powered on, with the display and four directional buttons visible" width="540">
</p>

## Current status

| Area | Status |
| :--- | :--- |
| Hardware and software | About 90% complete on the prototype |
| Enclosure / shell | Not made yet |
| Wiring documentation | Rev 1 connections recorded; remaining details flagged in the pinout |
| Firmware in this repository | Not uploaded yet |
| Custom PCB files | Hoped for in a future revision; not released |
| 3D print files | Hoped for in a future revision; not released |

This repository currently contains the build documentation, wiring reference, and selected photos. The prototype's software already exists, but its source and setup instructions are not included yet.

## Explore the build

- **[Full pinout and wiring notes](docs/pinout.md)** — power, serial, display, D-pad, and audio connections.
- **[Wiring diagram](docs/diagrams/rev1-wiring.svg)** — a zoomable overview of the documented connections.
- **[Connection list (CSV)](docs/pinout.csv)** — an editable list of connections and confirmation notes.
- **[Parts list](docs/hardware.md)** — components used and model details still to confirm.
- **[Photo gallery](docs/gallery.md)** — from loose parts to the powered prototype.
- **[Roadmap](docs/roadmap.md)** — the remaining Rev 1 work and possible future releases.

## How it fits together

The KB2040 reads the D-pad and talks to the DFPlayer Mini over serial. The display connects through the KB2040's I²C connector. Audio comes from the DFPlayer's left and right DAC outputs to the stereo jack. A battery, charger, switch, and voltage converter provide power.

![Rev 1 wiring overview, including power, UART, I2C, D-pad assignments, and stereo audio](docs/diagrams/rev1-wiring.svg)

The diagram records the supplied Rev 1 wiring. The D-pad return connections, exact charger/converter models, and audio jack lug positions still need confirmation. See the [pinout notes](docs/pinout.md#details-still-to-confirm) before copying the build.

## What's next

- Finish the enclosure and the remaining prototype work.
- Add the existing firmware and document its controls and setup.
- Confirm the remaining wiring and component details.
- Hopefully design and release a custom PCB.
- Hopefully release 3D printable case files once the fit is tested.

There is no release date for the PCB or case files yet. This repo will grow with the project.
