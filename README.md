🌊 ECHO: Survive by Sound 🧠

✨ A Game Born from Midterm Madness! ✨

🤯 Overview: What is ECHO?

Welcome to ECHO! This is a tense 2D survival/puzzle game developed by a small group of highly motivated (and slightly sleep-deprived) secondary school students. 😴

In ECHO, light is scarce, but sound is your superpower! You play as a character trapped in a dark environment and must use your unique ability—Echolocation—to momentarily reveal the hidden monsters and valuable loot around you.

We poured our blood, sweat, and tears (mostly stress tears from midterms) into this project, focusing on core mechanics like the togglable Sound Mode, a functional Inventory System, and real-time looting.

🎮 Core Features

ECHO is built around a few core, headache-inducing (in a good way!) features:

Icon

Feature

Description

🔊

Sound Mode Toggle

Press 'E' to enter Sound Mode! The screen instantly flips to grayscale, and your vision is replaced by sound waves that pulse automatically to reveal nearby objects.

👻

Object Revelation

Monsters and loot boxes are invisible in Normal Mode! When the sound wave hits them, they briefly glow with a vibrant high-contrast effect, giving you a chance to react!

🎒

Inventory System

A full 20-slot inventory grid! Items don't stack—every unique loot piece takes its own slot, forcing strategic resource management.

🗃️

Drag-and-Drop

Fully functional drag-and-drop support for swapping items between inventory slots. Time to organize that backpack!

☠️

Loot & Death Penalty

Collect randomized loot by searching containers! But be warned: if you die, your inventory is completely wiped (a truly painful post-midterm feeling).

🛠️ Getting Started

Ready to experience the auditory terror? Follow these simple steps!

Prerequisites

Unity Editor: Requires Unity 2022.3 or higher.

Required Packages: Make sure you have the Post Processing Stack installed via the Package Manager (since we use it for the Sound Mode visuals!).

Installation

1. Clone the Repository:

  git clone [https://github.com/yourusername/ECHO.git](https://github.com/yourusername/ECHO.git)


  Open in Unity: Open the cloned directory in the Unity Hub.

  Run the Scene: Navigate to the main scene file (e.g., Assets/Scenes/GameScene.unity) and hit the Play button!

2. Itch.io link:
   

Controls

Key

Action

Script Handled By

WASD

Movement

PlayerMovement.cs

E

Toggle Sound/Echolocation Mode

ModeManager.cs / PlayerMovement.cs

Mouse Click

Interact (Start Search on Lootable)

PlayerInteraction.cs (or similar)

Mouse Drag

Swap Inventory Slots

InventSlot.cs

💖 The Team (Secondary Student Survivors)

This project was developed entirely by secondary students who survived the absolute torment of midterm exams. Our brains are officially fried, but our code lives on! 🚀

"We coded it, we tested it, and now we're taking a nap. Enjoy the darkness!" 🌙

— The ECHO Dev Team
