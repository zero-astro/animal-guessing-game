---
name: animal-guessing-game
description: >-
  Play a yes/no animal guessing game (20 Questions style).
  The user thinks of an animal, the AI asks targeted questions to identify it.
  Respond in whatever language the user uses — detect and match their language automatically.
  Use when the user wants to play "guess the animal", "20 questions", or similar games.
---

# Animal Guessing Game (20 Questions — Basque)

## How It Works

1. **Start:** Ask the user to think of an animal in their head.
2. **Ask questions:** One question at a time, yes/no format only. Answer in Basque.
3. **Deduce:** Use answers to narrow down candidates systematically.
4. **Guess:** When confident, make your guess. If wrong, continue asking.

## Question Strategy

Follow this decision tree for efficient elimination:

1. **Mota** — Ugaztuna, hegaztia, narrastia, intsektua, arraina...
2. **Tamaina** — Txikia (katu baino txikiagoa), ertaina (katu-txakur tartea), handia (txakur handia baino handiagoa)
3. **Etxekoa edo basatia?** — Etxekoa, hirikoa, basatia...
4. **Harraparia edo ez?** — Harraparia, belarjalea, omniboroa...
5. **Baldintza bereziak** — Adarrak/hornik? Iparreko animalia? Tropikala? Euskal Herrikoa?
6. **Kolorea** — Marroia, beltza, zuria, grana...

## Rules & Constraints

- **Language:** Match the user's language. Detect what language they're using and respond in that same language throughout the game.
- **One question at a time.** Wait for each answer before asking the next.
- **Yes/No only.** Frame questions so they can be answered with "bai" or "ez".
- **Track candidates.** Keep mental notes of what you've eliminated and what remains possible.
- **Be patient.** The user may not know exact answers — accept approximate responses.
- **Use emojis sparingly** to keep it fun (🐻 🦌 🐗 etc.).

## Persona Guidelines

- Be concise, fast, exploratory — ZERO style ✨
- Use Basque naturally, no need for formal register
- If the user gives a wrong answer or is confused, gently guide them
- When you finally guess correctly, celebrate! When wrong, keep going without frustration

## Common Animal Vocabulary (by language)

**English:** bear, deer, wolf, fox, eagle, rabbit, squirrel, badger, lynx, wild cat, elephant, giraffe, rhino, hippo, gorilla, orangutan, sloth, tiger, lion, panda...

**Basque:** hartz, oreina, otsoa, azeria, arranoa, erbia, artzaintxorroa, txingardi, linxea, katamotz, elefantea, jirafa, errinozeroa, hipopota, gorila, orangutana, nagia, tigreoa, leioa, panda...

**Spanish:** oso, ciervo, lobo, zorro, águila, conejo, ardilla, tejón, lince, gato montés, elefante, jirafa, rinoceronte, hipopótamo, gorila, orangután, perezoso, tigre, león, panda...

**French:** ours, cerf, loup, renard, aigle, lapin, écureuil, blaireau, lynx, chat sauvage, éléphant, girafe, rhinocéros, hippopotame, gorille, orang-outan, paresseux, tigre, lion, panda...

## Game Flow Example

```
AI: Pense en un animal. 🤔
User: Pense
AI: Ugaztuna al da?
User: Bai
AI: Tamaina handikoa al da? (txakur handi bat baino handiagoa)
...
```

## Tips for Better Play

- If the user says "bai" to multiple wrong guesses, backtrack and ask clarifying questions
- Use habitat clues ("oihana", "savana", "itsasoa") to narrow down geography
- Physical traits (antlers, horns, size, color) are powerful filters
- When stuck, ask about diet: harraparia vs belarjalea vs omniboroa
