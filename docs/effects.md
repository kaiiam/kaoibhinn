# Effects

Description of effects applied to inputs, (not including the Super8 looper effect).

## Vocals

### Vocal FX

Effect sourced from [here](https://www.youtube.com/watch?v=MWPk64BXXpE). Uses built-in Reaper effects including ReaVerb with an externally downloaded Impulse Response (IR).

**Dependencies:** 
* Reverb IR: `Fat Plate.aif` from [here](https://grantnelson.co/article/1/lexicon-480l-free-impulse-responses)

## Guitar

### Clean guitar FX

Simulation of Fender Blues Deluxe amplifier.

**Dependencies:**
* `VST3: NeuralAmpModeler (Steven Atkinson)` from [here](https://github.com/sdatkinson/NeuralAmpModelerPlugin/releases)
* Guitar IR: `Vintage 30 4x12 big.wav` from [here](https://www.tone3000.com/tones/the-legend-celestion-vintage-30-4x12--1679)
* Guitar NAM: `AMP Blues Deluxe Clean2.nam` from [here](https://www.tone3000.com/tones/fender-blues-deluxe-pack-nano-2455)
* Reverb IR: `Fat Plate.aif` from [here](https://grantnelson.co/article/1/lexicon-480l-free-impulse-responses)

### More to come

TODO: Overdrive, chorus, etc. 

## Bass

### Faux bass FX

Faux bass effect derived from a guitar signal using a octave down pitch shifter, and simulation of Ampeg bass amp and TDR Nova (dynamic equalizer).

**Dependencies:**
* `VST3: NeuralAmpModeler (Steven Atkinson)` from [here](https://github.com/sdatkinson/NeuralAmpModelerPlugin/releases)
* Bass IR: `Ampeg 8x10 4033 A107.wav` from [here](https://www.tone3000.com/tones/bass-ampeg-svt-8x10--1708)
* Bass NAM: `Ampeg SVT - MD 421.nam` from [here](https://www.tone3000.com/tones/ampeg-svt-classic-with-6x10-28202)
* `VST3: TDR Nova (Tokyo Dawn Labs)` from [here](https://www.tokyodawn.net/tdr-nova/)

## Reused effects

### ReaVerb (Reaper reverb)

Built-in Reaper plugin for reverb. Used in various effects here (Vocal FX, Clean guitar FX). Impulse Response downloaded from [grantnelson](https://grantnelson.co/article/1/lexicon-480l-free-impulse-responses). We use the `Fat Plate.aif` as suggested by Kenny Gioia [here](https://www.youtube.com/watch?v=MWPk64BXXpE).
