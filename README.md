# Animal Guessing Game (20 Questions)

A yes/no animal guessing game for AI agents — inspired by the classic "20 Questions" party game.

The user thinks of an animal, and the AI asks targeted questions to identify it. One question at a time, with answers limited to "yes" or "no".

## How It Works

1. The user picks an animal in their head
2. The AI asks yes/no questions to narrow down candidates
3. Questions follow a logical decision tree: species → size → habitat → diet → physical traits → color
4. When confident, the AI makes a guess
5. If wrong, it keeps asking until it gets it right

## Features

- **Language detection** — automatically matches the user's language (English, Basque, Spanish, French, etc.)
- **Smart question strategy** — systematic elimination using a decision tree
- **Multi-language vocabulary** — built-in animal names in 4 languages
- **Flexible & patient** — handles approximate answers and confusion gracefully

## Installation

Copy the `animal-guessing-game/` directory into your OpenClaw skills folder:

```bash
cp -r animal-guessing-game ~/.openclaw/skills/
```

Or install via ClawHub if available.

## Usage

Once installed, simply say "play", "guess the animal", or "20 questions" and the AI will start the game automatically.

## File Structure

```
animal-guessing-game/
├── SKILL.md          # Agent instructions (loaded by OpenClaw)
└── README.md         # This file (human-readable documentation)
```

## License

Licensed under the Apache License, Version 2.0
