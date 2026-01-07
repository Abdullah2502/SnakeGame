# 🐍 Classic Snake Game in Java

A recreation of the classic Snake game built using Java Swing and AWT. This project demonstrates 2D graphics rendering, event handling, and basic game loop logic in Java.

## 🎮 Game Description

The player controls a snake that moves around a grid-based board. The objective is to eat apples to grow in length and increase the score. The game ends if the snake collides with the walls or its own body.

## ✨ Features

* **Classic Gameplay**: Smooth movement and growth mechanics.
* **Score Tracking**: Real-time score display at the top of the screen.
* **Collision Detection**: detect collisions with game borders (600x600 window) and self-collision.
* **Randomized Food**: Apples spawn at random grid positions.
* **Game Over Screen**: Displays the final score when the game ends.

## 🛠️ Tech Stack

* **Language**: Java
* **GUI Libraries**: `javax.swing`, `java.awt`

## 🚀 How to Run

### Prerequisites
Ensure you have the **Java Development Kit (JDK)** installed on your machine.

### Installation & Execution

1.  **Clone the repository** (or download the files):
    ```bash
    git clone [https://github.com/yourusername/snake-game-java.git](https://github.com/yourusername/snake-game-java.git)
    cd snake-game-java
    ```

2.  **Compile the source code**:
    Open your terminal in the project directory and run:
    ```bash
    javac Main.java GameFrame.java GamePanel.java
    ```

3.  **Run the game**:
    ```bash
    java Main
    ```

## 🕹️ Controls

The game is controlled using the keyboard arrow keys:

| Key | Action |
| :--- | :--- |
| **↑ Up Arrow** | Move Up |
| **↓ Down Arrow** | Move Down |
| **← Left Arrow** | Move Left |
| **→ Right Arrow** | Move Right |

## 📂 Project Structure

* **`Main.java`**: The entry point of the application. It initializes the `GameFrame` to start the application.
* **`GameFrame.java`**: Handles the main window window creation using `JFrame`. It sets the title to "Snake", handles window centering, and prevents resizing.
* **`GamePanel.java`**: The core game engine. It handles:
    * The game loop (`Timer`).
    * Painting components (Snake, Apple, Score, Grid).
    * Key listeners for movement input.
    * Game logic (movement, collisions, apple consumption).

## ⚙️ Configuration

You can tweak the game settings inside `GamePanel.java`:

```java
static final int WIDTH = 600;      // Window Width
static final int HEIGHT = 600;     // Window Height
static final int UNIT_SIZE = 25;   // Size of the snake/grid blocks
static final int DELAY = 75;       // Game speed (Lower is faster)

<img width="294" height="171" alt="image" src="https://github.com/user-attachments/assets/4d95d61c-e4bf-46a0-adf0-20d4a2832672" />
Created by Abdullah Rafi
