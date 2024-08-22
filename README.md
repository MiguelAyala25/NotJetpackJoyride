# JetpackJoyride clone made in unity

![main-menu](https://github.com/MiguelAyala25/NotJetpackJoyride/assets/108642172/f6c858dc-a1ed-4b54-8810-6480bde15f6d)

## 📝 About The Project

This game is an endless runner inspired by the popular Jetpack Joyride, where players control a character equipped with a jetpack to navigate through a series of obstacles, collect coins, and earn points. Developed as a team project, our goal was to build the most polished version of the game within an 11-week period, incorporating various gameplay mechanics and visual effects to enhance the user experience.

![Untitled video - Made with Clipchamp (1)](https://github.com/MiguelAyala25/NotJetpackJoyride/assets/108642172/a8d1b005-2c6e-45ef-b48c-92ae5ad6e6a8)


## 📖 Getting Started

Installation Instructions
Follow these steps to set up and run the Jetpack Joyride clone on your local machine.

Prerequisites:

- Unity 2021.3 or later: Download and install from Unity's official site.
- Git: Install Git from Git's official site to clone the repository.
- Clone the Repository
- Open Terminal or Command Prompt: Navigate to the directory where you want to clone the project.

1.  Clone the Repository: Use the following command to clone the project:

```bash
git clone https://github.com/MiguelAyala25/NotJetpackJoyride.git
```
2.  Navigate to the Project Directory:
```bash
cd jetpack-joyride-clone
```

3.  Open the Project in Unity, Navigate to the Assets/Scenes folder in the Unity Editor. Open the 00_Menu.unity scene and play the Game.


## Controlls!

Press space to jump and hold to activate the jetpack

## Features I worked on

🎮 Player Controller:

Manages the character's movement and interactions in the game, including jetpack mechanics, jumping, and collision handling. Below is a summary of the functionalities I    worked on:

Movement Mechanics:

- Jetpack Mode: Activates when the player holds the input, applying an upward force to simulate jetpack propulsion.
- Jump Mode: Triggers a jump force when the player is on the ground and presses the input.
- Gravity Mode: Applies a downward force simulating gravity when no input is detected or the player is mid-air without jetpack activation.
- Input Handling for desktop and mobile
- Fixed bugs and enhanced the feel of the movement.

CustomForces:

A customizable system that manages the forces applied to the player gives the feeling of controlling a jetpack:
- Gravity Force: Applied continuously unless jetpack or jump forces are active.
- Jetpack Force: Applied when jetpack is enabled, creating upward movement.
- Jump Force: Applied when a jump is initiated from the ground.
  
 ![image](https://github.com/MiguelAyala25/NotJetpackJoyride/assets/108642172/4498c127-9394-4dc9-b26c-c627ddbed9c0)



Collision Management:

- Ground Detection.
- Obstacle Collision.

NPCs:

- Developed NPCs (Non-Playable Characters) that react to player actions, enhancing the game's dynamic feel.

Animations:

- Configured animations for both NPCs and the player character, ensuring smooth transitions and engaging visuals.
  
Revive:

- Created a revive mechanich with the unity built in ad system.


## 📜 contributors
- [@twdaviss](https://github.com/twdaviss)
- [@LeahTaurisano](https://github.com/LeahTaurisano)
- [@tSleepingDragon0](https://github.com/SleepingDragon0)
- [@CultyMarble](https://github.com/CultyMarble)
- [@PhiBeo](https://github.com/PhiBeo)
- [@LNicholasOkovic](https://github.com/NicholasOkovic)
