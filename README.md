
# 10 MHz Crystal Oscillator with Signal Conditioning

## Objective
To design and simulate a 10 MHz crystal oscillator and improve its output waveform using a Schmitt trigger buffer for digital system compatibility.

## Stage 1: Crystal Oscillator
- Frequency: 10 MHz
- Output: Low amplitude sinusoidal waveform
- Simulation Tool: LTSpice

### Observation
The oscillator produced a sinusoidal waveform with limited amplitude, unsuitable for direct digital interfacing.

## Stage 2: Signal Conditioning using Schmitt Trigger
- Device Used: SN74LVC1G17
- Function: Hysteresis-based waveform shaping

### Result
The sinusoidal signal was converted into a clean square wave with improved rise time and noise immunity.

## Key Concepts
- Crystal-based frequency stability
- Hysteresis
- Signal integrity
- Rise time improvement
- Digital buffering

## Applications
- Microcontroller clock source
- RF system timing reference
- Embedded digital systems
