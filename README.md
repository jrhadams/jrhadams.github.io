## What is this?

This is my [Quarto]()-based personal website. Mostly just a scaffold right now, but nice proof of concept with Nix dependency management.

## How to build?

Install [Nix](https://nix.dev/install-nix.html) on your system and ensure that flakes are [enabled](https://nixos.wiki/wiki/Flakes). Then just run the following two commands:

```bash
nix develop
quarto render
```
