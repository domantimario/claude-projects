# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

A collection of small front-end projects built with Claude. Currently contains a Tic-Tac-Toe game. New projects will be added as standalone files or subdirectories over time.

## Running projects

No build step required. Open any `.html` file directly in a browser:

```
start tictactoe.html   # Windows
```

Or use a local dev server to avoid file:// quirks (e.g. fetch, modules):

```
npx serve .
```

## Project structure

Each project lives as either a self-contained `.html` file (HTML + CSS + JS in one file) or its own subdirectory. There is no shared framework or bundler.

## Git workflow

- Commit after every meaningful change with a short imperative subject line
- Push to `origin/master` (GitHub: https://github.com/domantimario/claude-projects) after each commit
- Keep commits scoped — one logical change per commit
