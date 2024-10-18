# tldro

This is my own offline version of tldr.

tldr can be annoying if you have a slow connection. It does not work if you are offline.

## Preparation

- Install `mdcat`

- Clone the tldr repo to your ~/.config

```bash
git clone https://github.com/tldr-pages/tldr ~/.config/tldro
```

- Clone this repo, save tldro to a local `~/bin` or `~/.bin` which is in your path

- use `tldro` instead of `tldr`

## Update Database

Go to ~/.config/tldro and do `git pull`
or, run 

```bash
tldro -u
```
