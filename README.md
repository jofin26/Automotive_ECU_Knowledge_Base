# ECU Knowledge Base

A personal reference site for understanding automotive Electronic Control Units — hardware, software, communication, and safety — from a safety manager's perspective.

## What is this?

A static website built as a learning tool for a new automotive safety manager. Each topic page provides:

- Plain English explanation with full context
- How the topic connects to the entire ECU system (hardware and software)
- Inline SVG diagrams showing signal flows, AUTOSAR layer stacks, and safety analysis
- ISO 26262 safety relevance and failure mode analysis
- Meeting survival vocabulary

## How it works

- Built with plain HTML and CSS — no frameworks, no build tools, no dependencies
- Hosted for free on GitHub Pages
- New topic pages are generated with Claude AI and uploaded here
- All diagrams are inline SVG — no external libraries required

## Structure

```
index.html          → Home page with domain categories
style.css           → Shared design system
404.html            → Friendly error page for missing topics
topics/
  adc.html          → ADC (Analog to Digital Converter)
  ...               → More topics added over time
```

## Domains

- **Hardware** — ADC, DAC, microcontrollers, sensors, actuators
- **Software / AUTOSAR** — MCAL, IoHwAb, RTE, SWC, interfaces
- **Communication** — CAN bus, LIN, SPI, signals, message routing
- **Safety / ISO 26262** — ASIL, FMEA, FTA, safety mechanisms, hardware metrics
