# Rusty – Xone:PX5 + Xone:K2 4-Deck FX Mapping (djay pro)

This example shows a real-world mapping used by Rusty with:

- **Xone:PX5** as the main 4-channel mixer and audio interface  
- **Xone:K2** as the MIDI brain for:
  - Deck 1–4 transport (play, cue, sync)
  - Library browsing and loading 1–4
  - Auto loops per deck
  - FX1 / FX2 / FX3 on all 4 decks with wet/dry control

The actual `.djayMidiMapping` file is included here:

```text
mappings/allen-heath/xone-px5/rusty-4deck-k2/Rustys-4-deck-with-effect-1.djayMidiMapping
```

You can use this as:

- A drop-in starting point for PX5 + K2 rigs.
- A reference when building your own mapping for 24C + K2 or other mixers.
- An example of how to structure and name mappings in Tha Mapping Lab.

## Usage

1. Place the mapping file in your djay pro MIDI mappings folder, or import it via **MIDI > Configure > Import**.
2. Select the mapping for your K2 / PX5 in the MIDI devices list.
3. Check the channel routing on the PX5 so that Deck 1–4 line up with djay's decks.

## Notes

- This mapping came originally from a PX5-focused setup and is meant for experienced users who are comfortable tweaking MIDI mappings.
- For a simpler 2-deck layout or Neural Mix stems, you can fork this mapping and strip it back.
