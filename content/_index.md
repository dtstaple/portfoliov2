---
name: "Davis Stapleton"
bio: "I'm a CS student at Syracuse University who likes building things close to the hardware. Past work includes HVAC firmware and validation in industrial automation, and automation tooling and database apps in fintech. Most of my interest is in embedded and low-level systems, though I work across backend and full-stack too."
description: "Davis Stapleton — portfolio."
links:
  - label: "LinkedIn"
    url: "https://www.linkedin.com/in/davisstapleton"
  - label: "GitHub"
    url: "https://github.com/dtstaple"
experience:
  heading: "Experience"
  items:
    - org: "Johnson Controls"
      role: "Software Engineering Intern, Systems Engineering Team"
      dates: "May–Aug 2026"
      points:
        - "Wired and flashed firmware onto BACnet building automation devices, standing up the lab test targets other teams ran against."
        - "Moved an internal UI regression suite from Selenium to Playwright and cut its runtime by 40%."
      tags: ["Python", "C/C++"]
    - org: "Loomis Sayles"
      role: "Software Engineering Intern, Backend Development"
      dates: "Jun–Aug 2025"
      points:
        - "Python and SQL Server tooling that processed 5,000+ transactions a day and generated the compliance team's reports."
        - "Refactored 2,000+ lines of legacy Perl into modular Python."
      tags: ["Python", "SQL"]
projects:
  - title: "CampSite"
    url: "#"
    meta: "Camping trip planner"
    images:
      - src: "/other/campsite.mp4"
        poster: "/other/campsite-poster.jpg"
        zoom: true
    description: "A tool for planning dispersed camping trips. It scores potential sites on things like distance to water, slope, trail access, land cover, and legal status, and writes out a short explanation for each score instead of just plotting dots on a map. It also plans multi-day routes using Dijkstra over a trail graph built from about 334,000 OpenStreetMap segments."
    results: "The OpenStreetMap segments don't share endpoints, so they needed snapping and merging in PostGIS before routing worked. Scores are kept per factor instead of averaged together, which is what the explanations are built from."
    tags: ["React", "TypeScript", "Django", "PostGIS", "Mapbox"]
  - title: "Weather Station"
    url: "#"
    meta: "STM32 weather station"
    images:
      - src: "/other/wstation.png"
      - src: "/other/wstationphys.png"
    description: "A small weather station built on an STM32 microcontroller. It reads temperature, humidity, and pressure from a BME280 sensor over I2C, shows the readings on a TFT screen, and sends them over UART to a Python script that forwards the data to an MQTT broker so it can be viewed on a simple web dashboard."
    results: "Raw BME280 output needs the sensor's calibration registers applied before it means anything, and the UART stream needed framing so Python could tell a full reading from a partial one. After that, the same reading feeds both the screen and the dashboard."
    tags: ["C", "STM32 HAL", "I2C/SPI", "Python", "MQTT"]
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
