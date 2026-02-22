# OSRS SFX Archive

Extracted Old School RuneScape sound effects (.synth files) from RuneLite cache.

## Contents

- `osrs_synth_extractor.py` - Python script to extract .synth files from RuneLite cache
- `synths/` - 11,203 extracted .synth files (idx4 - Sound Effects)

## Usage

```bash
# Extract specific
python3 tools/osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --ids 5876 5844 5822

# Extract between specifics
python3 tools/osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --start-id 5822 --end-id 5885

# Extract singular
python3 tools/osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --start-id 5876

# Extract all sounds
python3 tools/osrs_synth_extractor.py --cache ~/.runelite/jagexcache/oldschool/LIVE --all
```

## Sound Effect IDs

- `0370` - cow_death
- `2675` - protect_from_magic

See [OSRS Wiki](https://oldschool.runescape.wiki/w/Sound_effects) for full list.

## License

Sound effects are property of Jagex Ltd.
