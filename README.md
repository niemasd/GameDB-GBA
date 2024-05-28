# GameDB-GBA
Nintendo Game Boy Advance (GBA), part of [GameDB](https://github.com/niemasd/GameDB).

## Structured Downloads
* **[`GBA.data.json`](https://github.com/niemasd/GameDB-GBA/releases/latest/download/GBA.data.json):** All data, structured in the JSON format
* **[`GBA.data.tsv`](https://github.com/niemasd/GameDB-GBA/releases/latest/download/GBA.data.tsv):** All data, structured in the TSV format
* **[`GBA.release_dates.pdf`](https://github.com/niemasd/GameDB-GBA/releases/latest/download/GBA.release_dates.pdf):** Histogram of release dates, stratified by region
* **[`GBA.titles.json`](https://github.com/niemasd/GameDB-GBA/releases/latest/download/GBA.titles.json):** Mapping of serial numbers to game titles, structured in the JSON format

# Notes

## Uniquely Identifying Games

The game folders in [`games`](games) have the structure `XXXX`, where `XXXX` is the game code (also known as game ID), which is at offsets `0xAC` through `0xAF` (inclusive) of the ROM header, and which can be used to uniquely identify the game.

# Sources
* [No-Intro](https://no-intro.org/)
