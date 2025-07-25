# Synthesizer Spec Sheet

## Overview
This repository contains a simple web-based music composer/synthesizer implemented in `mcomp.html`. The interface allows users to select musical scale, waveform type, tempo, volume, note length, and compose music using an 8x16 grid.

## Features
- 8x16 grid for placing notes across 8 rows and 16 columns.
- Support for multiple scales: C Major, D Major, A Minor.
- Multiple waveform options: sine, square, triangle, sawtooth.
- Adjustable tempo (60-240 BPM), volume (0-1), and note length (100-1000 ms).
- Play/Pause functionality with visual indication of the current column.
- Save and load compositions via `localStorage`.
- Export compositions to MIDI format using Tone.js MIDI library.

## File Structure
- `mcomp.html`: Main HTML file containing the user interface and synthesizer logic.
- `README.md`: Basic README placeholder.

## How to Run
Open `mcomp.html` in a modern web browser with JavaScript enabled. Interact with the grid to place notes, choose settings, then click "Play" to hear the composition. Use "Save" and "Load" to store compositions locally, and "Export MIDI" to download a MIDI file.

