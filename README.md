# Termux Configuration Tools

A small collection of Termux customization/configuration files and an installer helper.

## What it contains

- `.termux/` — Termux terminal configuration assets
- `bash.bashrc` — shell prompt, aliases, colors, and interactive shell settings
- `execute.php` — helper script that copies the configuration into Termux paths and reloads Termux settings

## Important behavior

The installer script writes to Termux configuration locations under `/data/data/com.termux/`. Review the files before running it because it replaces shell/terminal configuration.

## Typical environment

This repository is intended for Termux/Android environments with PHP available.

> This is a configuration utility collection, not a general-purpose PHP application.
