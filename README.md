# AUC Digital Game Design : 2D Basics For Programmers

## 🚀 Welcome to Your First Unity 2D Game Development Journey!

This tutorial is an **essential step** in your learning journey. Unity's official [2D Adventure Game: Robot Repair](https://learn.unity.com/course/2D-adventure-robot-repair?version=6.3) course covers the fundamental aspects of 2D game development. If you do not **complete the entire course**, you will face significant difficulties when designing and implementing your own game in the coming weeks.

## ✅ Prerequisites

Before you begin, make sure you have:

- Installed **Unity Hub** and **Unity 6000.3.26f1** (Unity 6.3 LTS). This is the exact version the project uses (see `ProjectSettings/ProjectVersion.txt`); Unity Hub will offer to install it when you open the project.
- Completed the [Unity Essentials](https://learn.unity.com/pathway/unity-essentials) pathway, including its [2D Essentials](https://learn.unity.com/pathway/unity-essentials/unit/2d-essentials) unit. Robot Repair assumes you already know your way around the Editor.
- Completed the **GitHub starter assignment**, so you are comfortable with cloning, committing and pushing.

## 📥 Getting Your Repository

- Open the **assignment link** shared in class and accept it. This creates your own **private** repository in the AUC-Game-Design organization, named after the classroom, the assignment and your GitHub username.
- **Clone** that repository to your computer.
- **Do not rename your repository.** Renamed repositories disappear from grading.

## 📂 Opening the Project in Unity

- Launch Unity Hub.
- Click **Add** → **Add project from disk** and select the folder you cloned.
- Open the project. If Unity Hub asks you to install the matching editor version, accept. If it offers to **upgrade** the project to another version, **decline**.

### 🎮 Jump Straight into Development

We have already created the project from the **Universal 2D** template, imported the course assets and removed the files you don't need. In other words, step 5 of the Welcome tutorial ("Create a new project and import the project assets") is already done for you.

- Read the **Welcome to 2D Adventure Game: Robot Repair** tutorial for orientation, but **skip step 5**.
- The finished example game (`Tutorial_Demo`) has been removed from this project, so step 6 ("Play the example game") won't work here.
- For the same reason, in Unit 6's **"Extra things to add"** tutorial, skip the parts that open the demo scenes or the demo `StartScreen`. If you want a main menu, build your own.
- **Start directly** at **"Set up a 2D player character"**.

### 🎨 Pick Your Theme

The course comes with three asset sets: **Ruby's Adventure**, **Sugar Land** and **Ducko**. Each lives in its own folder under `Assets/_2DAdventureGame/Art`, with the same file names, so the instructions work whichever one you pick. You can also mix sprites from different sets.

## 📜 Requirements and Grading

- The due date will be communicated in class.
- To complete this assignment, you must **work through all six units** of the course:
  1. **Player character and movement**
  2. **Game environment and physics**
  3. **Health system**
  4. **Characters and interaction mechanics**
  5. **Game UI and game loop**
  6. **Enhance your game**
- Successfully finishing these units will guarantee you a **B+ grade**.

### 🔖 One Commit per Unit (Mandatory)

Every time you finish a unit, **commit and push immediately**, before starting the next unit. The commit message must follow this exact format:

```
Unit 1 complete: Player character and movement
Unit 2 complete: Game environment and physics
Unit 3 complete: Health system
Unit 4 complete: Characters and interaction mechanics
Unit 5 complete: Game UI and game loop
Unit 6 complete: Enhance your game
```

- By the end of the assignment, your repository must contain **all six completion commits**, in order.
- **Push each completion commit as soon as you finish the unit.** GitHub records when every push arrives, so six unit commits pushed together at the end count as **one end-of-assignment commit**, not as six units completed over time.
- Committing more often than this is welcome: the six completion commits are the minimum, not the maximum.
- Each completion commit must contain the **finished work for that unit**, and the project must open and play at that point.
- Commit your original enhancement (see below) **after** the Unit 6 commit, so it is clearly separate from the course work.
- Your history is part of your submission: **do not squash, rewrite or force-push** it.
- To earn an **A- or A**, you must go beyond the course and **implement an original enhancement** to the game you developed throughout it. This could include:
  - **A new mechanic**
  - **An improvement of an existing mechanic**
  - **Other creative modifications**
- You must **commit all files and push your work to the repository** to count as a submission. If you do not push your work, it **will not be considered**, and you will receive an **F**.
- Your repository comes with a **Feedback pull request**. **Do not merge or close it**

## ⚠️ Important Warnings

- **Disk Space**: Ensure you have at least **4GB of free space** before opening the project. Unity generates temporary files and downloads necessary packages during the project's lifecycle.
- **Preferred IDE**:
  - If you're on **Windows**, use **Visual Studio Community**, which you can add as a module when installing Unity from Unity Hub. It is already configured for Unity projects.
  - If you're on **Mac**, use **Visual Studio Code** with the **Unity** extension. The project already recommends it when you open the folder in VS Code.
  - **JetBrains Rider** also works on both platforms.
  - In Unity, check that your IDE is selected under **Preferences** → **External Tools** → **External Script Editor**.
- **Version Control**: Always commit the `.meta` files that Unity creates next to your assets. The `Library`, `Temp` and `Logs` folders are already excluded by `.gitignore`; never force-add them.

## 🏆 Get Started Now!

Mastering these basics will **empower you** to create your own unique 2D games in the weeks ahead. Happy coding! 🎮🔥
