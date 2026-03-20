# Pokemon Flutter App 🎮

A retro-style Pokemon game built from scratch using the Flutter framework. This project recreates the nostalgic feel of the Game Boy Advance era, specifically drawing inspiration from Pokemon Emerald, Ruby, and Sapphire. It features map exploration, sprite-based animations, and a turn-based battle system.

## 🌟 Features

* **Retro Game Boy UI:** A custom-built user interface that mimics the classic handheld console, complete with a functional D-pad and A/B buttons.
* **Sprite Animations:** Smooth walking cycles for the main character and NPCs, implemented by cycling through sprite sheets.
* **Map Exploration:** Detailed recreation of "Littleroot Town" and the "Pokemon Lab," including seamless map transitions when entering or exiting buildings.
* **Collision Detection:** Logic-based "No-Man's Land" system to prevent characters from walking through walls, houses, or environmental objects.
* **Turn-Based Battles:** A functional battle system featuring Pikachu vs. Charmander, including health bars, animated character entries, and attack logic.
* **NPC Interaction:** Dynamic interaction with Professor Oak, including dialogue bubbles and directional facing logic.

## 🛠️ Tech Stack

* **Framework:** [Flutter](https://flutter.dev/)
* **Language:** [Dart](https://dart.dev/)
* **State Management:** `setState` and `Timer`-driven logic for game loops and animations.
* **Layout:** Utilizes `Stack`, `Column`, `Row`, and `AspectRatio` for a responsive and consistent game-screen experience.

## 📂 Project Structure

```text
lib/
├── characters/     # Character sprite logic (Boy, Oak, Pokemon)
├── maps/           # Map definitions (Littleroot, Pokemon Lab, Battleground)
├── images/         # Asset folder containing sprite sheets and map tiles
├── utilities/      # Reusable UI components (Health bar, buttons, chat bubbles)
└── main.dart       # Main game engine and UI orchestration
