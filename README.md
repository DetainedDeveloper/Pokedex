# Pokedex
JSON data of 890 pokemons in both, a [single file](https://github.com/DetainedDeveloper/Pokedex/tree/main/pokedex_raw) and a [categorized folder](https://github.com/DetainedDeveloper/Pokedex/tree/main/pokedex) in **`array[]`** and **`map{}`** structures. Scraped using [Pokemon Data Scraper](https://github.com/DetainedDeveloper/Pokemon-Data-Scraper)

- For some reason, pokemon data **after 890**, was either empty or started with indexes **above 10000**
- That's why, I recommend only using **890** pokemons for projects

### pokedex_raw

- **`pokedex_raw`** contains data of all **890** pokemons in a single file
- **`pokedex_raw_array.json`** contains **`array`** of **890 `objects`**
- **`pokedex_raw_array.json`** contains **`map{}`** of **890 `{ pokemon_name : data }` pairs**

### pokedex

- **`pokedex`** also has data in both, [**`array`**](https://github.com/DetainedDeveloper/Pokedex/tree/main/pokedex/array) and [**`map{}`**](https://github.com/DetainedDeveloper/Pokedex/tree/main/pokedex/map)
- I made the data categorized for **`pagination`**
- Each **`pokedex_<number>.json`** contains data of **50** pokemons
- Except **`pokedex_18.json` (93)** and **`pokedex_22.json`(7)**