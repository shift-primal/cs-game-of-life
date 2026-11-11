# Game of Life

Conway's Game of Life in the terminal, written in C#. The grid is sized to fit the console window.

## Run

Requires the .NET 10 SDK.

```sh
dotnet run
```

The start screen lets you choose a speed from 1 to 5 (1000, 500, 250, 100 or 50 ms per generation).

## Controls

| Key | Action |
| --- | --- |
| Space / P | Pause and resume |
| → | Step one generation (while paused) |
| + / ↑ | Faster |
| − / ↓ | Slower |
| Esc / Q | Quit |

## Layout

- `Core/`: grid, cells and the simulation loop
- `Rendering/`: drawing the grid and the status bar
- `Config/`: start screen and speed settings
- `Memory/`: stored generations
- `Debug/`: file logger
