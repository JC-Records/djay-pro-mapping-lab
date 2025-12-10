# Djay Pro Mapping Lab

Community-driven MIDI mappings, DVS setups, and controller guides for **Djay Pro**.

This repo is a central hub for anyone trying to make Djay Pro work nicely with:

- Allen & Heath mixers and controllers (Xone:24C, K2, K3, PX5, DB series)
- Pioneer, Reloop, Denon, Numark, Hercules and other MIDI devices
- Hybrid setups using external mixers, interfaces, timecode and DVS
- Custom-built or non-standard controllers that need hand-made mappings

If you have a mapping that works, a routing diagram that saved your sanity, or notes that might help someone else, drop it here and help the community.

---

## Goals

- Share fully working Djay Pro MIDI mapping files  
- Make DVS and audio routing easier to understand  
- Document quirks, fixes, and tips for specific controllers  
- Provide a single directory for all Djay Pro mapping resources  
- Let DJs collaborate, tweak, improve, and evolve the ecosystem  

This repo exists so people don’t have to remap their gear at 2am while crying.

---

## Repo Structure

```text
mappings/
  allen-heath/
    xone-24c/
    xone-k2/
    xone-k3/
    px5/
  pioneer/
  reloop/
  denon/
  numark/
  generic-midi/

docs/
  setup/
    djay-pro-install-mappings.md
    enable-dvs-guide.md
    audio-routing-examples.md
  controllers/
    xone-24c-notes.md
    xone-k2-layering.md
    generic-midi-tips.md
  troubleshooting/
    dvs-issues.md
    midi-debugging.md

examples/
  rusty-jay-xone24c-k2-setup.md
  4deck-layout-example.png
This structure grows as the community contributes.

How to Use This Repo
Open the folder for your controller or mixer

Download the mapping file(s)

Follow the README.md notes in that folder

Drop the file into Djay Pro’s mapping directory

Restart Djay and select it under MIDI devices

If you’re using DVS, check the docs/setup/ folder for routing guides.

Contributing
Pull requests are welcome.

When adding a new mapping
Include:

The mapping file

A README.md next to it with:

Djay Pro version tested

OS used (macOS, Windows, iOS)

Controller/mixer/interface model

Deck layout (2deck, 4deck, FX layers, etc)

Any known issues

Name files clearly:

pgsql
Copy code
xone-24c-djaypro-macos-v1.xml
ddj-400-djaypro-win-4deck-v2.xml
generic-rotary-2deck-template.xml
Issues
Open an Issue if:

A mapping needs fixing

You want a device mapped

Your DVS setup does weird stuff

Djay sees the controller but nothing works

Someone created a mapping and you just want to say “thank you”

Include OS, Djay Pro version, device model and your routing.

License
MIT License

Use, modify, remix, share — totally open.

Why This Repo Exists
Because configuring Djay Pro with unsupported gear can feel like a trial sent by the gods.

If something in here saves even one DJ from rage-quitting after mapping a controller for six hours, this repo has fulfilled its destiny.

Share your knowledge.
Help the next person.
Keep the underground alive.
