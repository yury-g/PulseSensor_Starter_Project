# Big Eye Context

## What Big Eye is

Big Eye is the next-generation PulseSensor exploration platform: a visibly larger, more expressive PPG sensor concept with multiple LEDs, richer visualization, and better science/debugging workflows.

It is not just a smaller wearable sensor. It is a teaching, prototyping, and visualization platform for photoplethysmography.

## Core idea

Make PPG visible, beautiful, and understandable.

Big Eye should help people see:

- Raw heartbeat waveform.
- Inter-beat intervals.
- BPM.
- Respiration effects.
- Signal quality.
- LED/color differences.
- Placement differences: finger, palm, wrist, ear.
- Frequency-domain information such as FFT.
- Time-domain and frequency-domain views together.

## Why it matters

PulseSensor is already loved because it makes heart-rate sensing approachable. Big Eye should expand that into a more serious but still playful platform:

- More LEDs.
- More test modes.
- Better visual feedback.
- Better educational explanations.
- Better hardware debug workflows.
- Better manufacturing/QC story.

## Important product instinct

Do not make Big Eye feel like a generic medical device.

It should feel like:

- Science instrument.
- Maker tool.
- Teaching demo.
- Beautiful visualization engine.
- Open hardware platform.

## Current hardware direction

Explored or discussed:

- Multiple LEDs: green, red, IR, possibly more wavelengths.
- Large-format sensor face.
- Better mechanical interface to finger/palm.
- Possible locking connector instead of fragile soldered harness.
- Arduino/ESP32-friendly signal path.
- Integration with Seeed XIAO ESP32S3, CYD ESP32 display boards, M5Stack devices, and browser dashboards.
- Possible GPIO-controlled sensor power for sleep / battery prototypes.
- Coating / encapsulation exploration for skin contact and durability.

## Current visualization direction

The desired visualization language is scientific but expressive:

- Oscilloscope view.
- FFT / frequency-domain view.
- Tachogram / IBI view.
- HRV and respiration-aware views.
- Orthographic / CAD-like scientific visualization.
- Isometric ridgelines / wave landscapes.
- Particle/comet/wireframe visualizations.
- Multi-user overlapping heart/breath signals.

## Design warning

Do not over-dramatize the visuals so much that the science gets lost. The goal is emotionally engaging scientific visualization, not fake medical theater.

## Preferred phrase

Big Eye should make PPG feel real, inspectable, and alive.