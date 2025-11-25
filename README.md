🎮 Catch the Falling Objects — Java 2D Game

A simple 2D Java Swing game where you control a basket and try to catch falling objects. Great as a starter game project and easy to extend or customize!

🖼 Game Preview (Text Mock Output)

Since this is a lightweight Swing game, here’s a console-style mock-up showing what the game looks like when running:

Score: 3
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│            []                   []                           │
│                                      []                      │
│                       []                                     │
│                                                              │
│                                                              │
│                                                              │
│                                                              │
│--------------------------------------------------------------│
│                            ██████████                        │
└──────────────────────────────────────────────────────────────┘


Legend

[] = falling red squares

██████████ = player basket

Score displayed at top-left

When you run the Java file, you’ll see the same layout but rendered with colors in a window (white background, red objects, blue basket).

🚀 Features

Smooth 60 FPS animation

Keyboard controls (Left/Right arrows)

Randomly generated falling objects

Increasing difficulty through random speeds

Clean and simple Java Swing implementation

📦 How to Run
1. Clone the repo
git clone https://github.com/yourusername/catch-the-falling-objects.git

2. Compile the game
javac Game.java

3. Run it
java Game

🎮 Controls
Key	Action
⬅ Left Arrow	Move basket left
➡ Right Arrow	Move basket right
📁 Project Structure
/project-folder
 ├── Game.java
 ├── README.md
 └── (optional) assets/
       └── screenshot.png



If you take an actual screenshot of the game window, place it in assets/ and link it like:

