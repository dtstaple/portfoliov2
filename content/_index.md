---
name: "Davis Stapleton"
bio: "Short bio here — who you are, what you build, what you're into."
description: "Davis Stapleton — portfolio."
links:
  - label: "LinkedIn"
  - label: "GitHub"
    url: "https://www.linkedin.com/in/davisstapleton"
projects:
  - title: "CampSite"
    url: "#"
    meta: "Full-stack geospatial web app"
    images:
      - src: "/other/campsite.mp4"
        poster: "/other/campsite-poster.jpg"
        zoom: true
    description: "A planner for dispersed backcountry camping that scores candidate sites 0–100 on water, slope, trail access, land cover, legal status, and weather. Rather than just drawing the data on a map, it explains every score in plain language — \"nearest stream 408m off, plan to carry enough for the evening\" — and plans multi-day routes with Dijkstra over a trail graph built from ~334,000 OSM segments."
    tags: ["React", "TypeScript", "Django", "PostGIS", "Mapbox"]
  - title: "Project two"
    url: "#"
    meta: "What it is · Year"
    description: "One or two sentences about it."
    tags: ["Tech", "Tech"]
other:
  heading: "Other Work"
  description: "A mix of smaller projects I've put together."
  items:
    - title: "Serial Debug Console"
      url: "https://github.com/dtstaple/serial_console_v1"
      images:
        - src: "/other/serialconsole.png"
          zoom: true
      blurb: "A desktop serial terminal for debugging microcontrollers. Instead of dumping raw UART text that scrolls by too fast to read, it lays the stream out as a structured table with timestamps, time between messages, and color-coded log levels you can filter."
      tags: ["C++", "Qt6"]
    - title: "PHY 307 computational physics project"
      images:
        - src: "/other/physsim1.png"
          zoom: true
        - src: "/other/physsim2.png"
          zoom: false
      blurb: "A pair of orbit simulations built for computational physics. One shows a single orbit that slowly rotates the way Mercury's does when you bend gravity slightly, and the other runs a multi-planet system that keeps checking its own energy to prove the math is holding up"
      tags: ["C++", "ffmpeg"]
    - title: "Proof checker"
      images:
        - src: "/other/logicsim.png"
          zoom: true
      blurb: "A tool from my PHI 251 logic class that checks formal proofs written in TFL and FOL. You enter a proof line by line and it verifies each step follows the rules, flagging anything invalid."
      tags: ["HTML"]
---
