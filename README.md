# MUD Game Skeleton

Welcome to the MUD (Multi-User Dungeon) Skeleton Project — a lightweight and flexible starting point for building your own text-based multiplayer adventure game.

This framework is for developers who want to create a MUD from scratch, customize their own game logic, and add content without having to build the entire structure from the ground up.

---

## Features

- Modular directory layout for easy navigation and scalability
- Simple C++ source files to customize the game loop and logic
- Separation of concerns between game data, build files, and source code
- Makefile included for quick compilation

---

## Project Structure

```
MUD/
├── build/      # Compiled output and executables
├── db/         # Game data (rooms, items, NPCs, etc.)
├── src/        # Core source code (game engine, server loop, etc.)
├── makefile    # Build configuration
```

### `src/`
- Contains the core server logic for your MUD.
- You can expand this with new classes, systems, and logic for game features like combat, movement, chat, or quests.

### `db/`
- This is where you store your game's content:
  - Maps and room descriptions
  - Items, weapons, and treasures
  - NPCs and scripted events
- This directory is designed for creators to easily plug in new content.

### `build/`
- Output directory where the compiled binaries are stored after running `make`.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nicholasj898/MUD.git
cd MUD/MUD/develop
```

### 2. Build the Project

Make sure you have `make` and a C++ compiler installed (e.g., `g++`), then run:

```bash
make
```

This will compile the source files and create the executable in the `build/` folder.

### 3. Run the Server

After building:

```bash
./build/mud
```

*(Replace `mud` with your executable name if different.)*

---

## Add Your Own Creations

- To customize the game, edit or add new `.cpp` or `.h` files in the `src/` folder.
- To add new content (items, rooms, events), place data files or scripts into the `db/` folder.
- Recompile using `make` to reflect your changes.


## Contributions

Have ideas to improve the skeleton? Want to share new game mechanics or tools? Feel free to fork the repo, submit pull requests, or create issues.

---

Happy coding, and good luck building your world!