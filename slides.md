---
title: Hexasound and face-modulation
separator: ---
verticalSeparator: -v-
revealOptions:
  transition: 'slide'
---

## Hexasound & face-modulation

<div style="font-size: 4em;">⬢🔊🤪</div>

-v-

## What did sound look like again

-v-

* Amplitude
* Frequency
* Phase

-v-

These can be modulated

* Frequency Modulation
  * Example
* Amplitude Modulation
  * Example
* Phase Modulation
  * Example

-v-

## Combining these modulations

* The quad example
* The hexagonal example

---

## WebAudio API

* There's an audio graph
* Some Nodes
  * Sources
  * Sinks
  * Oszillators
  * Mixers
  * Script
* Audiocontexts
  * Online, depending on user interaction
  * Offline, for speed

---

## Nonsense 1: face-modulation

-v-

* The project idea
* Faithfully face-modulated phase-modulation!

-v-

* Example code on how to module the phase

---

## Nonsense 2: Hexasound

-v-

There was this video by `CGP Grey`: [Hexagons are the bestagons](https://www.youtube.com/watch?v=thOifuHs6eY)

-v-

Well - Hexagons `are` the bestagons, but the sound is not hexagonal enough, is it?

-v-

### The plan

* Rerender video to include even more Hexagons.
* Rerender audio to be more hexagonal.
* Combine for profit!

---

## What is hexagonal sound

* I dunno - we just made that one up 🤷‍♀️
* Sound that doesn't go like this:
* But sound that goes like this:

-v-

### Use a WaveShaping node

How does this look?

-v-

* Partial success
* Partial loss

-v-

### Use a Filterbank

* Dissect signal into bands and recombine
* Use WaveShaping on bands
* Recombine bands

Alas perfect reconstruction is hard

-v-

### Use FFT/DFT

* Perfect reconstruction is solved
* Journey to the heart of the FFT
  * Analyser Node
  * Several Code examples later
* Reconstruction is annoying

-v-

### Just wing it

* Hexagons hate this trick
* Let's get it over with
* Link resulting video here
