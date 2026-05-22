# Evan Rovelli

Backend and systems engineer. Java, Rust, AWS.

## Current projects

**[tidyup](https://github.com/erovelli/tidyup)** · Rust, Tokio, ONNX Runtime, SQLite, Dioxus

On-device CLI + desktop app that classifies files by content, not extension. 11-crate hexagonal workspace with a 3-tier inference cascade (heuristics → ONNX embeddings → optional local LLM). Default binary links no HTTP client and no LLM runtime, enforced by a CI privacy audit. Atomic bundle moves with BLAKE3 verification and run-keyed rollback.

**[Medicaid Dental Utilization Atlas](https://github.com/erovelli/medicaid-dent-policy)** · TypeScript, React, MapLibre GL, PostgreSQL, Python · [Live site](https://erovelli.github.io/medicaid-dent-policy/)

Interactive choropleth mapping U.S. Medicaid dental claims across all 50 states at state and ZIP3 granularity, 2018-2024. Transforms ~60 GB of raw HHS and NPPES provider data into a ~5 MB static site with feature-state-driven recoloring, lazy-loaded monthly drill-down and zero backend infrastructure.

**[utils](https://github.com/erovelli/utils)** · Rust, WebAssembly

Browser-based utilities compiled from Rust to WASM. No data harvesting, no ads, no tracking. Currently includes a deterministic password generator. Auto-deploys to GitHub Pages on push.

## Smaller tools

**[strava-forwarder](https://github.com/erovelli/strava-forwarder)** · Python, Strava API, Google Sheets API

Polls Strava for Apple Watch fitness sessions and writes activity names and durations to a shared Google Sheet on a daily cron. Built to support group accountability without a third-party app in the middle.

## Past work

**[ModuLoop](https://github.com/cpcurtin/SDP-Team-28)** · C++, ARM Cortex-M7, I2S, QSPI, SPI

Hardware music sequencer on a Teensy 4.1. Led software architecture and hardware integration for a 4-engineer senior design team at UMass Amherst. MVC navigation over a custom struct tree, QSPI PSRAM sound cache to defeat SD latency, persistent track storage via ArduinoJSON. 4-sound polyphony, ±2% timing accuracy at 200 BPM.

## Day job

Full Stack Engineer at Fidelity Investments. Batch platforms, billing systems, AWS infrastructure, Spring Boot. Previously Associate Software Engineer and two-time intern at the same company.

## Links

- [LinkedIn](https://www.linkedin.com/in/erovelli)
