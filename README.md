# Bungee Jumping Simulation

This project is a multi-processing simulation of a bungee jumping game using C. The simulation involves three teams of players performing bungee jumps, coordinated by a referee process. The program uses signals and pipes for inter-process communication and visualizes the game using OpenGL.

## Project Structure

The project has the following structure:

```plaintext
bungee_simulation/
├── bin/                        # Contains the compiled executable
├── config.txt                  # Configuration file with game settings
├── include/                    # Header files for each module
│   ├── assistant_referee.h     # Assistant Referee module header
│   ├── player.h                # Player module header
│   └── config.h                # Config module header for loading settings
├── obj/                        # Compiled object files for each source file
├── src/                        # Source code files
│   ├── main_referee.c          # Main file that starts the game & Referee module implementation
│   ├── assistant_referee.c     # Team module implementation
│   ├── player.c                # Player module implementation
│   └── config.c                # Config module implementation to load settings
├── Makefile                    # Makefile for building the project
└── README.md                   # This readme file
```

## 