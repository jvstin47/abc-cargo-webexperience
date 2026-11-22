# ABC Cargo — Global Intermodal Freight & Maritime Experience

> An award-winning, commercial-grade digital experience for **ABC Cargo Group Inc.**, showcasing purposeful user interaction, precision scroll-driven product rendering, real-time satellite telemetry, and an interactive 3D fleet cylinder.

Built in **pure vanilla HTML5, CSS3, and JavaScript** with **zero external frameworks and zero build steps**.

🌐 **Live Experience:** [https://jvstin47.github.io/abc-cargo-webexperience/](https://jvstin47.github.io/abc-cargo-webexperience/)  
🎥 **Standalone KV Hero Demo:** [https://jvstin47.github.io/abc-cargo-webexperience/kv-hero.html](https://jvstin47.github.io/abc-cargo-webexperience/kv-hero.html)

---

## 🌟 Key Interactive Capabilities

### 1. Scroll-Driven Freight Handling Hero
* **97-frame 4K/1080p Reach-Stacker Handling Scrub**: The reach-stacker lifts a navy shipping container, rotates toward camera, and lowers it onto an arriving black semi-truck trailer in pure unoccluded white space.
* **Camera Pullback & Rising Ground Band**: At 3.1s–3.75s, the camera pulls back and the flat ground line naturally rises from $82.9\% \to 44.8\%$, landing flush with the truck wheels.
* **Giant Typography Gliding Behind Cargo**: Light-grey `ABC CARGO · GLOBAL INTERMODAL` giant caps (Anton, line-height 0.8) glide behind the semi-truck via `mix-blend-mode: darken` without breaking the vehicle silhouette.
* **Real-Time Telemetry HUD**: Live speedometer reading scroll delta ($|\Delta y|/\Delta t$), transit speed in knots, terminal berth coordinates, and payload mass.
* **5-Card Service Strip**: Ocean Container Lines, Container Drayage, Reefer Cold Chain, Heavy-Haul Rigging, and Air Charters slide in along the $44.8\%$ horizon with text reveal gradients.

### 2. Mission-Critical Industry Solutions
* **Lifesciences & Cryo-Pharma**: GDP-certified $-80^\circ\text{C}$ to $+25^\circ\text{C}$ active monitoring, dry-ice re-icing hubs, and tarmac transfer protocols.
* **Automotive JIT Sequencing**: Synchronous supply corridors with guaranteed 2-hour port-to-plant block trains.
* **Aerospace & Project Rigging**: Up to 850 MT SPMT modular hydraulic transporters and floating naval derrick barges.
* **Hazmat & Clean Tech Energy**: Class 1–9 lithium battery pressure-relief container holds and IMDG Level 3 compliance.

### 3. 3D Cylindrical Ocean Fleet Ring
* **16-Slot Cylindrical Fleet Ring**: 3D perspective projection ($r = 1800\text{px}$) rotating over a sunlit turquoise ocean plate with real-time water reflections.
* **Substepped Spring Physics**: Unconditionally stable double-step damped spring mechanics ($k=150, c=27$) handling drag, wheel, and touch gestures with zero jitter.
* **Interactive Vessel Specifications**: Clicking any 3D card opens a technical specification modal with high-definition video, TEU capacity, propulsion details, and direct capacity reservation.

### 4. Dynamic Freight Rate & Scope-3 Carbon Calculator
* Real-time calculation across major deep-sea trade corridors (Shanghai, Rotterdam, Singapore, Los Angeles, Hamburg, Dubai, Busan).
* Live equipment breakdown (40ft High Cube, 40ft Reefer, 20ft Standard, 45ft Pallet-Wide, Flat Rack).
* Automatic calculation of line-haul base, BAF bunker adjustment, terminal handling (THC), and green biofuel offset savings.
* **Official Bill of Lading Generator**: Generates an authentic logistics Bill of Lading with dynamic reference ID, barcode, and printable waybill styling.

### 5. Satellite AIS Live Shipment Tracking Drawer
* Slide-out glassmorphic drawer for real-time container and B/L lookup (`ABCU-984210-4`, `TITN-55291-0`, `GLBL-10294-8`).
* Live telemetry dials: Reefer core temperature, satellite GPS waypoint, knots over ground, and G-force shock sensor.
* 5-point milestone voyage progress timeline with completed timestamps.
* One-click clipboard export for standardized **EDI 310 Freight Status Notice**.

### 6. Interactive Global Port Route Radar
* Stylized dark SVG maritime map with illuminated Transpacific, Asia-Europe Silk Arc, and Transatlantic trade lanes.
* Clickable port nodes (Rotterdam, Singapore, Shanghai, Los Angeles, Dubai) displaying real-time crane move rates, channel drafts, container dwell times, and local weather/tide advisories.

### 7. Governance, Certifications & Ambient Acoustic
* Audited accreditations: ISO 9001:2015, ISO 14001:2015, ISO 27001, C-TPAT Tier 3, AEO-F Full Operator, IATA Cargo Agent, and BIMCO Member.
* **Synthesized Maritime Audio**: Built-in client-side sound engine synthesizing 12s oceanic rolling wave swells and 55Hz engine room harmonics via native Web Audio API (zero external audio files).
* **Floating Quick Action Dock**: Persistent bottom pill providing instant one-click access to Track, Rate Calc, Port Map, and Instant Quote.

---

## 💻 Tech Stack & Architecture

* **Frontend**: Pure HTML5, CSS3 (CSS Variables, Flexbox, Grid, 3D CSS Transforms, Mix-Blend-Mode, Backdrop-Filter), Vanilla ES6+ JavaScript.
* **Audio**: Native Web Audio API (BiquadFilterNode, LFO OscillatorNode, Pink/White Noise Buffer, GainNode).
* **Media Assets**: CloudFront-hosted scrubbed video frames and Kling 3 ocean plate loops.
* **Dependencies**: **0** (No React, Vue, Webpack, Vite, or npm build step required).
* **Responsiveness**: Fully responsive across all devices from $320\text{px}$ mobile screens up to $4\text{K}$ ultra-wide monitors.

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/jvstin47/abc-cargo-webexperience.git
cd abc-cargo-webexperience

# Start a local static HTTP server
python3 -m http.server 8000

# Open in your browser
open http://localhost:8000/
```

---

## 📄 License

MIT License © 2026 Justin. Created for portfolio and commercial design demonstration.
