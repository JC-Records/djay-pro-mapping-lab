# Tha Mapping Lab

Community hub for **djay pro** MIDI mappings, DVS setups and controller layouts.

This repo is meant to be a central place where people can:

- Share working djay pro mappings for any controller or mixer  
- Show how they wired DVS and audio routing  
- Document weird quirks and how they fixed them  
- Copy real world example setups like Xone:PX5 + K2, 24C rigs, DDJ, Denon, Reloop and more  

If you got it working and it is not trash, share it.

---

## Folder layout

All mappings live under `mappings/`, grouped by brand or type.

```text
mappings/
  allen-heath/
    xone-24c/
    xone-k2/
    xone-k3/
    xone-px5/
  pioneer/
    ddj-400/
    ddj-800/
    cdj-setups/
  denon/
  reloop/
  numark/
  native-instruments/
  hercules/
  roland/
  other/
    generic-midi/
    custom-builds/

docs/
  setup/
  controllers/
  troubleshooting/

examples/
  px5-k2-rusty-4deck.md
```

If you add something for a brand that does not exist yet, create a new folder under `mappings/` for it.

---

## How to add a mapping

1. Go to `mappings/<brand>/<device>/`
2. Upload your mapping file  
3. Add a small `README.md` in that folder that explains:
   - djay pro version and OS  
   - device model and firmware  
   - what the mapping is for (2-deck, 4-deck, DVS, stems, FX etc)  
   - any known issues

Example file names:

```text
xone-24c-djaypro-macos-2deck-v1.djayMidiMapping
ddj-400-djaypro-win-4deck-v2.djayMidiMapping
generic-rotary-2deck-template.djayMidiMapping
```

---

## Example mapping: Xone:PX5 + K2 (Rusty 4-deck FX rig)

A full real-world mapping is included under:

```text
mappings/allen-heath/xone-px5/rusty-4deck-k2/
```

and documented in:

```text
examples/px5-k2-rusty-4deck.md
```

Use it as a reference for structure, naming and README style.

---

## Contributing

Pull requests are welcome.

- Add mappings in the correct brand folder  
- Keep names clear and simple  
- Add notes so the next DJ knows what you did  
- Use Issues for mapping requests, problems or suggestions  

The goal is simple.  
Less time rage-mapping, more time playing music.
