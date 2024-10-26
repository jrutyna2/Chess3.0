# Chess2.0 for Java

## Overview
Chess2.0 is a 2-player chess game implemented in Java with a graphical user interface (GUI). The game allows users to play chess by interacting with a visual board, highlighting legal moves for selected pieces, and determining the winner when checkmate occurs. Chess3.0 will incorporate an AI computer chess player!

## Technology
- **Java**: The core programming language used for implementing the game.
- **Swing**: Java's built-in library for GUI components.
- **ImageIO**: For loading and rendering chess piece images.
- **Data Structures**: Includes arrays for board representation and `HashMap` for tracking legal moves.

## Prerequisites
Before running the game, ensure that you have the following:
- **Java Development Kit (JDK)** installed on your machine.
  - **Check Java Installation**:
    - Open a terminal (Mac) or command prompt (Windows) and run:  
      `java -version`  
      If Java is installed, you should see the version information.
    - If not installed, download it from [Oracle's official site](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) and follow the installation instructions.

## Instructions

### Windows
1. **Open Command Prompt**:
   - Press `Win + R`, type `cmd`, and hit Enter.

2. **Navigate to the Project Directory**:
   - Use `cd` to change to the directory where your Chess2.0 files are located. For example:  
     `cd C:\path\to\chess2.0\`

3. **Compile the Java Files**:
   - Run the following command to compile the source code:  
     ```bash
     javac -d bin -sourcepath src src/*.java
     ```

4. **Run the Program**:
   - Start the game by running:  
     ```bash
     java -cp bin GameWindow
     ```

### Mac
1. **Open Terminal**:
   - Press `Cmd + Space`, type "Terminal", and hit Enter.

2. **Navigate to the Project Directory**:
   - Use `cd` to change to the directory where your Chess2.0 files are located. For example:  
     `cd ~/path/to/chess2.0/`

3. **Compile the Java Files**:
   - Run the following command to compile the source code:  
     ```bash
     javac -d bin -sourcepath src src/*.java
     ```

4. **Run the Program**:
   - Start the game by running:  
     ```bash
     java -cp bin GameWindow
     ```

## How to Play
- **Move Pieces**: Click on a piece to select it. The legal moves will be highlighted, and you can click on the highlighted squares to move the piece.
- **Winning the Game**: The game ends when either white or black is checkmated. If white is checkmated, a message will appear saying, "Black wins!"

Enjoy playing Chess2.0!
