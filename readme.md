## ♟️ chess.html: The Strategic Mobile Trainer

This is the official `README.md` for **chess.html**, a mobile-first application designed to help players master the game by always playing as the White pieces. Focus on strategic decision-making is reinforced with a constant, integrated hint system.

### ✨ Key Features

* **Ultra-Lightweight Footprint:** The application is extremely small, weighing in at only **32 KB**, ensuring rapid downloads, minimal storage use, and high performance even on older devices.
* **Fixed Perspective:** The user **always plays as White**. This consistent viewpoint allows for deeper study and mastery of White's opening principles and strategic advantages.
* **AI Opponent (Black):** The AI bot plays as Black, challenging the user with varied strategies based on the chosen difficulty level.
* **Integrated Best-Move Hint:** A **visual guide/directional hint** is shown **at all times** on the board, indicating the optimal move for the user (White) based on the AI's current evaluation. This is a core learning tool.
* **Full Rules Compliance:** The engine strictly adheres to all standard FIDE chess rules, including:
    * Standard piece movements (Pawn, Knight, Bishop, Rook, Queen, King).
    * Special moves: **Castling** (Kingside & Queenside), **En Passant**, and **Pawn Promotion**.
    * Game-ending conditions (Checkmate, Stalemate, Draw by 50-move rule/threefold repetition).
* **Mobile-First UI/UX:**
    * **Responsive & Touch-Friendly:** Designed for natural, effortless interaction on smartphones and tablets.
    * **Rectangular, No-Scroll Layout:** The entire game state (board, hint, and UI elements) is contained within a fixed, non-scrolling rectangular layout, ensuring all critical information is visible instantly.

### 📱 User Interface (UI) Layout

The application utilizes a constrained, rectangular layout for maximum clarity on mobile screens:

| Section | Content | Description |
| :--- | :--- | :--- |
| **Top Bar** | Score, Game Status (e.g., "White to Move," "Check") | Essential game information. |
| **Middle Section (Board)** | Chess Board, Pieces, **Best-Move Hint Overlay** | The primary interaction area. The hint is visually subtle but clear. |
| **Bottom Section** | Controls (Undo, History, Settings), Move Log | Auxiliary features and action buttons. |

***

### ⚙️ Game States and Rules

The app displays clear visual and text notifications for the following game states:

* **Winning:** **Checkmate** (White's victory).
* **Losing:** **Checkmate** (AI's victory).
* **Draw:** **Stalemate**, **Threefold Repetition**, or **50-Move Rule**.
* **Check:** A clear indicator when the King is in check.

### 🛠️ Optional/Planned Features

These features enhance the user experience and training capabilities:

1.  **AI Difficulty Levels:** Implement several adjustable difficulty settings for the AI bot (e.g., Beginner, Intermediate, Expert).
2.  **Move History and Review:** A panel to scroll through the moves of the current game (in algebraic notation).
3.  **Undo/Redo Functionality:** Allow the user to step back or forward one or more moves to explore alternative lines.
4.  **Settings Menu:** Options to change board/piece themes, toggle sound effects, and adjust difficulty.

***

