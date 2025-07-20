# Connect Four

This is a classic Connect Four game implemented as an Android application. The game is played on a 7x6 grid, and the goal is to be the first player to get four of your colored discs in a row, either horizontally, vertically, or diagonally.

## Features

*   **Classic Connect Four Gameplay:** Play against another player on the same device.
*   **Simple Interface:** A clean and intuitive interface for a seamless gaming experience.
*   **Game Options:** Choose from different difficulty levels to match your skill.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Android Studio
*   An Android device or emulator

### Installation

1.  **Clone the repo:**
    ```sh
    git clone https://github.com/Betsyyvc/Connect4.git
    ```
2.  **Open the project in Android Studio:**
    *   Open Android Studio.
    *   Click on "Open an existing Android Studio project".
    *   Navigate to the cloned repository and select the `Project` folder.
3.  **Run the app:**
    *   Click the "Run" button (the green triangle) in Android Studio.
    *   Select an available Android device or emulator.

## How to Play

1.  The game starts with an empty board.
2.  Players take turns dropping their colored discs from the top into a column of their choice.
3.  The first player to get four of their discs in a row (horizontally, vertically, or diagonally) wins the game.
4.  If the entire board is filled and no player has four in a row, the game is a draw.

## Project Structure

*   `app/src/main/java/com/example/connectfour/MainActivity.java`: The main entry point of the application.
*   `app/src/main/java/com/example/connectfour/ConnectFourGame.java`: Contains the core game logic.
*   `app/src/main/java/com/example/connectfour/BoardFragment.java`: The UI for the game board.
*   `app/src/main/java/com/example/connectfour/GameOptionsFragment.java`: The UI for the game options.
