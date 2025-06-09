# My Personal WezTerm Configuration

This README provides a single shell command to download my **personal `.wezterm.lua` configuration file** directly from my Git repository to your `$HOME` directory on Unix-like systems.

---

## What is WezTerm?

**WezTerm** is a modern, high-performance terminal emulator focused on customization and advanced features. It offers GPU-accelerated rendering and Lua-based configuration, with `.wezterm.lua` being the central file for its personalization.

---

## The Download Command

To download my `.wezterm.lua` file and save it to your `$HOME`, use the command below:

```bash
git clone --depth 1 https://github.com/fefortunato/wezterm /tmp/temp_wezterm && mv /tmp/temp_wezterm/.wezterm.lua "$HOME"/.wezterm.lua && rm -rf /tmp/temp_wezterm
