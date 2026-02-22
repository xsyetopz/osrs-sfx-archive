# OSRS SFX Archive

Extracted Old School RuneScape sound effects (.synth files) from RuneLite cache.

## Contents

- `osrs_synth_extractor.py` - Python script to extract .synth files from RuneLite cache
- `synths/` - 11,203 extracted .synth files (idx4 - Sound Effects)

## Usage

```bash
# Extract from RuneLite cache
python3 osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --out ./synths

# Extract specific sound effect
python3 osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --out ./synths --start-id 370 --end-id 370
```

## Sound Effect IDs

- `0370` - cow_death
- `2675` - protect_from_magic

See [OSRS Wiki](https://oldschool.runescape.wiki/w/Sound_effects) for full list.

## License

Sound effects are property of Jagex Ltd.
