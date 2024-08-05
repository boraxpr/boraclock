# Bora clock
Bora Clock is a desktop clock app built using Tauri and SvelteKit. It combines the elegance of SvelteKit for the frontend with the power and efficiency of Tauri for creating cross-platform binaries. This project serves as a modern alternative to Electron-based desktop applications, offering a lightweight and efficient solution.

- Currently using https://svelte.dev/examples/clock as the base for the clock UI.

## Technology Used

- Tauri (Rust): Backend and build tooling
- SvelteKit (JavaScript): Frontend framework

## What is Tauri?

Tauri is a cutting-edge framework for building binaries for all platforms using web technologies. It provides a new way to build desktop applications, offering a lightweight and fast alternative to Electron.

## Why Tauri?

- Lightweight: Unlike Electron, which runs a browser in the background, Tauri uses the system's webview to render the UI, making it faster and more efficient.
- Efficient: Tauri applications have a smaller footprint and lower memory usage compared to Electron apps.

Think of popular applications like Microsoft Teams and Discord, which are built using Electron. While Electron offers great UI compatibility by running a browser in the background, it can be heavy and slow. Tauri, on the other hand, achieves similar goals with better performance and efficiency.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Svelte](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).
