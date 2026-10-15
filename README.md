# Tic-Tac-Toe (Ow)

A clickable Tic-Tac-Toe game with a modern UI (web or native desktop).

Written in **[Ow](https://github.com/OW-Programing-Language/ow-lang)** in an
object-oriented style — **one class per file**.

## Structure

```
src/
  Board.ow     # class Board — the 3x3 grid + win detection
  helpers.ow   # mark(), other() helpers
  Game.ow      # class Game — turn state, rules, renders the UI
  main.ow      # entry point (main)
```

## Run it

Install Ow (download from the
[ow-lang releases](https://github.com/OW-Programing-Language/ow-lang/releases) —
the native installer needs no Java), then:

```sh
ow run src/main.ow
```

Or open `src/main.ow` in **OwIDE** and press **Run ▶** (or **UI Native ▶** /
**UI Web ▶** for the graphical versions).

## License

[MIT](LICENSE).
