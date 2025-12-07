# C++ Console Multi-Wordle

A terminal-based game where a single player tackles multiple, simultaneous Wordle boards at once. Test your vocabulary and deductive reasoning skills by managing several word puzzles in a single command-line interface session!

## 🚀 Features

*   **Simultaneous Boards:** Play multiple, independent Wordle games displayed side-by-side or stacked in your console.
*   **Classic Wordle Mechanics:** Use color-coded feedback (e.g., green, yellow, grey text) to guess letters.
*   **Configurable Difficulty:** The number of simultaneous boards can be adjusted (likely in the source code or via a future command-line argument).
*   **Pure C++ Console App:** Lightweight and self-contained, requiring no external dependencies or internet connection.
![image info](./image.png)


## ⬇️ Installation and Setup

To play the game, you need to download and run the pre-compiled executable for your operating system.

### Prerequisites

*   A compatible operating system (Windows, macOS, or Linux).
*   A terminal or command prompt application with support for ANSI color codes for optimal viewing (most modern terminals support this).


1.  **Clone the Repository:**

2.  **Build and launch the Game:**
    ```bash
    source launch
    ```

## 🎮 How to Play

The objective is to solve all active Wordle boards simultaneously.

*   **Input:** Type a 5-letter word and press `Enter`. This single guess is applied to *all* active boards at the same time.
*   **Feedback:** Each board updates independently with standard Wordle feedback:
    *   **Green:** Correct letter in the correct spot.
    *   **Yellow:** Correct letter in the wrong spot.
    *   **Grey:** Letter is not in the word.
*   **Winning:** Continue guessing until all boards successfully reveal their hidden words within the maximum number of attempts.

## 🧑‍💻 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you find a bug or have a suggestion for improvement.

