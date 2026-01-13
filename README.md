# ScoundrelFree

A simple web-based implementation of the Scoundrel card game.

## How to Play

Scoundrel is a solitaire card game where you battle monsters using a modified 52-card deck.

- **Monsters**: All spades and clubs.
- **Weapons**: All diamonds.
- **Potions**: All hearts.

Note: Hearts and diamonds face cards (J, Q, K) are excluded from the deck.

Start with 20 health. Draw cards to fill your hand (the room with monsters). Play weapons to equip, potions to heal. Select attack type (Bare Hands or Weapon), then click monster cards to attack. Weapons weaken by 1 after each use and persist until replaced; training allows fighting stronger monsters once. Flee to take damage and replace the monster, but can only flee once in a row. Defeated monsters and used potions go to discard; weapons only when replaced.

Goal: Clear all monsters from the room without your health reaching zero.

## Running the Game

Open `index.html` in a web browser or serve the directory with a local server (e.g., `python -m http.server`).

Navigate to the Game page to play, or Instructions for rules.