# PGL/1

**PGL/1 is code for a surround-sound virtual synthesizer project. Thje project is finished, and it is unlikely to be updated further.**

Written in SuperCollider, it combines four electronic sound generators, control-rate modulators, sequenced streams, MIDI control, and spatialization for VBAP or Ambisonic speaker layouts. The main application provides a control surface for routing, envelopes, effects, output, and live parameter changes.

## Project files

- `pgl_1_gui.scd` - main application and GUI
- `synthdef_entro.scd` - generator, modulator, and spatializer SynthDefs
- `settings.conf` - local audio and output settings
- `experiments/` - earlier and experimental interfaces with alternative control-matrix prototype

## Requirements

- SuperCollider
- Speaker output matching one of the included VBAP or Ambisonic configurations
- A MIDI controller for the controller mappings in `pgl_1_gui.scd` (optional)

Open `pgl_1_gui.scd` in the SuperCollider IDE and evaluate it. Review `settings.conf` and update the SynthDef and output paths for your local installation before use.

## License

MIT. See [LICENSE](LICENSE).
