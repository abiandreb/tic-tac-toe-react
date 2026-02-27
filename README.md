# Tic-Tac-Toe

A classic tic-tac-toe game built with React while learning the fundamentals of the library.

<img width="1701" height="1306" alt="image" src="https://github.com/user-attachments/assets/f640eaa5-e9ab-413c-ba6f-e21991d6acc8" />


## What I used

- **React 19** — components, props, JSX
- **Vite** — fast dev server and build tool
- **useState** — for managing game turns, player names, and edit mode

## What I learned

- How to **lift state up** — the game turns live in `App` and get passed down to child components, keeping everything in sync
- **Deriving state** instead of duplicating it — the active player, the board, and the winner are all computed from `gameTurns` rather than stored in separate state variables
- **Immutable state updates** — copying arrays/objects before modifying them so React picks up changes correctly
- How to **conditionally render** components (game over screen, edit/save button, active player highlight)
- Splitting the UI into small, focused components: `Player`, `GameBoard`, `GameOver`, `Log`
- Updating state based on **previous state** using the callback form of `setState`

## How to run

```bash
npm install
npm run dev
```
