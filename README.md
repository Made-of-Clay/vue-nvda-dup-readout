# Vue 3 + Vite

This is a test project to illustrate a duplicate text problem I'm having. Maybe the community will have some ideas to how to solve this issue.

Running [NVDA](https://www.nvaccess.org/download/) version 2024.4.2.35031

## Repro Steps

1. Start the Vue app - `pnpm dev`
2. Start NVDA
3. Load the page

The screen reader will read out "foo input" twice. (Is that correct?)

**Alternative 1:** If you run the `no-build.html` file on a file server, you'll get the same results.

**Alternative 2:** If you run the `vanilla.html` file on a file server, which has 0 Vue but effectively the same logic, you'll get the same results.

NVDA readout fragment of `vanilla.html` page load.

```
Vanilla Repro

Foo Input Foo Input   
```