from pathlib import Path
readme = """# Countries & Nationalities - Classroom Game Show

Interactive classroom game for practicing **countries, nationalities, pronunciation, listening, sentence building, and cultural clues** in **American English - Level 1**.

**Presented by Team Santiagos**

## Live game

Open the activity here:

https://sspuentes13.github.io/countries-nationalities-game/

## Purpose

This activity is designed as a dynamic team competition for the classroom. Students practice:

- Countries and nationalities
- Basic sentence construction
- Listening comprehension
- American English pronunciation
- Cultural associations
- Teamwork and oral participation

## How the game works

1. Divide the class into **two teams**.
2. Each team chooses a name.
3. The roulette randomly selects which team plays.
4. Each round has **3 challenges**.
5. Teams have **30 seconds** per question.
6. The team discusses the answer and chooses **one representative** to answer aloud.
7. The representative should change after every question so that everyone participates.
8. A team needs at least **2 correct answers out of 3** to secure the round.
9. If the team gets only 0 or 1 correct answer, the other team enters **Steal Mode**.
10. In Steal Mode, the second team receives a reformulated question and can steal the points.

## Difficulty progression

### Level 1 - Recognize
- Country -> nationality
- Nationality -> country
- Flags
- Multiple-choice questions
- Basic listening
- Printed-card challenges

### Level 2 - Build
- Sentence building
- Mini-dialogues
- He / She structures
- Capitals
- Grammar correction

### Level 3 - Communicate
- Listening and inference
- Cultural clues
- Team conversation chains
- Comparing countries
- Role play

## Audio

The activity uses the browser's **English (United States)** text-to-speech voice.

Students can:
- Hear the question again
- Hear a model answer
- Replay the model answer more slowly

For the best experience, use **Safari on iPad** or a modern version of **Chrome / Microsoft Edge** with an English (US) system voice installed.

## Warm-up activity - Memory Relay

Before the digital game, use the printed memory cards.

- Place all cards face down on a table.
- Make two team lines facing the table.
- One student from each team plays at a time.
- The student turns over one card and tries to find its matching card.
- Valid matches include:
  - Country + nationality
  - Country + cultural symbol / clue
- If the pair is correct, the team keeps it.
- If it is incorrect, both cards return face down in the same positions.
- The student goes to the back of the line and the next teammate plays.
- The team with the most correct pairs wins the warm-up.

Whenever possible, students should also say the match aloud, for example:

> France - French  
> Japan - Japanese

## Recommended class flow

| Stage | Suggested time |
|---|---:|
| Organize teams and explain rules | 2 min |
| Memory Relay warm-up | 8 min |
| Transition and game setup | 2 min |
| Digital Game Show | 20 min |
| Quick closing review | 3 min |

## Countries included

- United States - American
- United Kingdom - British
- France - French
- Italy - Italian
- Japan - Japanese
- China - Chinese
- Brazil - Brazilian
- Mexico - Mexican
- Canada - Canadian
- Germany - German
- Egypt - Egyptian
- Colombia - Colombian

## Technology

This project is a single-page classroom application built with:
- HTML
- CSS
- Vanilla JavaScript
- Web Speech API
- HTML Canvas
- GitHub Pages

No installation is required for students.

## Deployment

The site is published with **GitHub Pages** from the `main` branch and the repository root.

The main entry file must be named exactly:

`index.html`

## Credits

Designed for an English Level 1 classroom activity.

**Presented by Team Santiagos**
"""
path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print("Created", path)
