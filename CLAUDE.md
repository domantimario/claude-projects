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

After completing any piece of work — a new feature, a bug fix, a new project file — always:

1. `git add <files>` — stage only the relevant files
2. `git commit -m "..."` — short imperative subject line (e.g. `Add restart button to snake game`), with a bullet-body if more context helps
3. `git push` — push immediately to `origin/master` (https://github.com/domantimario/claude-projects)

Never leave work uncommitted or unpushed. Every session should end with a clean `git status` and the remote fully up to date. This ensures no work is ever lost and the GitHub history is always a reliable snapshot of the current state.
