---
name: "Davis Stapleton"
bio: "CS student at Syracuse University who likes building things close to the hardware. Past work includes HVAC firmware and validation in industrial automation, and automation tooling and database apps in fintech. Most of my interest is in embedded and low-level systems, though I work across backend and full-stack too."
description: "Davis Stapleton — portfolio."
links:
  - label: "LinkedIn"
    url: "https://www.linkedin.com/in/davisstapleton"
  - label: "GitHub"
    url: "https://github.com/dtstaple"
projects:
  - title: "CampSite"
    url: "#"
    meta: "Camping trip planner"
    images:
      - src: "/other/campsite.mp4"
        poster: "/other/campsite-poster.jpg"
        zoom: true
    description: "A tool for planning dispersed camping trips. It scores potential sites on things like distance to water, slope, trail access, land cover, and legal status, and writes out a short explanation for each score instead of just plotting dots on a map. It also plans multi-day routes using Dijkstra over a trail graph built from about 334,000 OpenStreetMap segments."
    tags: ["React", "TypeScript", "Django", "PostGIS", "Mapbox"]
  - title: "Weather Station"
    url: "#"
    meta: "STM32 weather station"
    images:
      - src: "/other/wstation.png"
      - src: "/other/wstationphys.png"
    description: "A small weather station built on an STM32 microcontroller. It reads temperature, humidity, and pressure from a BME280 sensor over I2C, shows the readings on a TFT screen, and sends them over UART to a Python script that forwards the data to an MQTT broker so it can be viewed on a simple web dashboard."
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
