LEGION — Global Awareness System
StatusVersionLicenseNodes

Real-time tactical monitoring and global situational awareness dashboard.

Overview
LEGION is a self-contained, browser-based global awareness system that provides a God's-eye view of a distributed network of monitoring nodes. It features an interactive world map with live node tracking, signal intelligence feeds, network event streams, and threat assessment panels — all running entirely client-side with zero dependencies on external APIs or backend services.

Features
Interactive World Map
Canvas-rendered tactical map with simplified continent outlines
24 nodes positioned at real-world coordinates across all continents
Animated connection arcs with traveling data-packet indicators
Pan (click + drag), zoom (scroll wheel), and node selection (click)
Crosshair targeting reticle on selected nodes
Real-time latitude/longitude cursor tracking
Node Monitoring
Color-coded status indicators: Online (green), Warning (amber), Critical/Offline (red)
Node classifications: HQ, Relay, Sensor, Outpost
Live telemetry: signal strength, bandwidth, latency, uptime
Dynamic threat assessment with visual bar graphs
Mini traffic chart with auto-updating intervals
Live Intelligence Feeds
SIGINT Feed — Signal intelligence intercepts, frequency sweeps, directional fixes
Network Events — Route optimizations, mesh topology changes, link status
Alert Stream — Intrusion attempts, thermal alerts, threat escalations, resolutions
All feeds auto-generate context-aware messages using real node designations
Dynamic Simulation
Node signal strength fluctuates in real-time
Occasional status transitions (online ↔ warning)
Threat levels shift dynamically
Traffic charts animate independently
Header stats update every second (UTC clock, node count, aggregate threat, data rate)
Tech Stack
Layer	Technology
Markup	Single HTML5 file
Styling	Custom CSS with CSS Variables
Rendering	HTML5 Canvas 2D
Fonts	Google Fonts (Orbitron, Share Tech Mono)
Icons	Font Awesome 6
Logic	Vanilla JavaScript (ES6+)
Backend	None — fully client-side
Getting Started
Quick Start
No build tools, no install, no server required.

# Clone the repositorygit clone https://github.com/ShannonCodesAI/Legion.gitcd Legion# Open in your default browseropen index.html# or on Linux:xdg-open index.html# or on Windows:start index.html
That's it. The dashboard loads and begins simulating immediately.
