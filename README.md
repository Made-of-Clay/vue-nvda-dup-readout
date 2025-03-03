# Vue 3 + Vite

This is a test project to illustrate a duplicate text problem I'm having. Maybe the community will have some ideas to how to solve this issue.

Running [NVDA](https://www.nvaccess.org/download/) version 2024.4.2.35031

## Repro Steps

1. Start the Vue app - `pnpm dev`
2. Start NVDA
3. Load the page

The screen reader will read out "foo input" twice. (Is that correct?)
