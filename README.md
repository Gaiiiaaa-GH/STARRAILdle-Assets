# STARRAILdle-Assets

A clean, ready-to-use set of Honkai: Star Rail character art and icons — portraits, splash art, skill icons, and the small badge icons for elements, paths, and weekly bosses.

Pulled together for [STARRAILdle](https://github.com/Gaiiiaaa-GH/STARRAILdle), a Wordle-style daily guessing game for HSR. Sharing it here in case it's useful for your own project, or if you just want the images without scraping them yourself.

## What's inside

```
icons/                small character avatar icons
portraits/              character bust portraits (close-up)
splash_art/             character full splash art scenes
skills/                  ability icons, one per real type (Basic ATK/Skill/Ultimate/Talent/Technique)
type_icons/
  elements/               Physical, Fire, Ice, Lightning, Wind, Quantum, Imaginary
  paths/                   Destruction, Hunt, Erudition, Harmony, Nihility, Preservation, Abundance...
  bosses/                  weekly boss material icons
```

Every folder has a `manifest.json` listing each file's exact width/height, so you know what you're getting before downloading anything individually.

## Source

Everything here comes from [Mar-7th/StarRailRes](https://github.com/Mar-7th/StarRailRes), the community resource repo used by most HSR fan tools. This repo doesn't add anything StarRailRes doesn't already have — it's just re-organized under clearer folder names and pre-sorted per character.

One thing worth knowing if you go digging in StarRailRes yourself: its `preview` field is actually the tight bust crop (→ our `portraits/`), and its `portrait` field is the big splash scene (→ our `splash_art/`) — backwards from what the names suggest.

## Keeping this up to date

This repo is refreshed by hand, not on a schedule — the local refresh script isn't published here, just used to re-check StarRailRes before anything gets committed. StarRailRes itself updates fast after every patch, so it's usually the freshest link in the chain.

## Credits

Character designs, names, and all game content belong to HoYoverse / COGNOSPHERE. Data and assets sourced via [Mar-7th/StarRailRes](https://github.com/Mar-7th/StarRailRes). This is an unofficial, non-commercial fan resource.
