# Clawd Pixel Codex Pet

![Clawd Pixel preview](preview.svg)

A fan-made pixel Clawd pet for Codex. It keeps the simple orange blocky Clawd look, with connected limbs, square black eyes, and a cleaner animated spritesheet for idle, waiting, running, review, failed, and directional movement states.

For the full animation QA sheet, see [`contact-sheet.png`](contact-sheet.png).

## Install

Download [`clawd-pixel.zip`](https://github.com/UknownPerson/clawd-pixel-codex-pet/raw/main/clawd-pixel.zip), then unzip it into:

```text
%USERPROFILE%\.codex\pets\clawd-pixel\
```

The final folder should contain exactly these two runtime files:

```text
%USERPROFILE%\.codex\pets\clawd-pixel\pet.json
%USERPROFILE%\.codex\pets\clawd-pixel\spritesheet.webp
```

Restart Codex or reload the pet list after copying the files.

## Ask Codex to install it

You can also give Codex this prompt:

```text
Install this Codex pet from GitHub: https://github.com/UknownPerson/clawd-pixel-codex-pet
Use pet id clawd-pixel. Download pet.json and spritesheet.webp from the repository root and place them in %USERPROFILE%\.codex\pets\clawd-pixel\.
```

Direct runtime files:

- [`pet.json`](https://raw.githubusercontent.com/UknownPerson/clawd-pixel-codex-pet/main/pet.json)
- [`spritesheet.webp`](https://raw.githubusercontent.com/UknownPerson/clawd-pixel-codex-pet/main/spritesheet.webp)

## Files

- `pet.json`: Codex pet manifest.
- `spritesheet.webp`: Runtime spritesheet used by Codex.
- `clawd-pixel.zip`: Install package containing only `pet.json` and `spritesheet.webp`.
- `preview.svg`: Compact README preview.
- `contact-sheet.png`: Full QA image for checking all animation states.

## Notes

This is an unofficial, fan-made pet for personal Codex customization. It is not affiliated with, endorsed by, or sponsored by Anthropic or Claude. No `LICENSE` file is provided; please treat this as a personal-use share rather than a reusable commercial asset.
