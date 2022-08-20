# Pokémon API

## Pokémon API using Github Pages

<img src="pokeball.png" alt="pokeball" style="width: 100px; height: auto;"/>

<br>

## API links

[Pokémon API index page](https://arindampal-0.github.io/pokemon-api/)

[Pokémon api link](https://arindampal-0.github.io/pokemon-api/index.json)

<br>

## How to use the API

### Get all Pokémon list

[https://arindampal-0.github.io/pokemon-api/index.json](https://arindampal-0.github.io/pokemon-api/index.json)

```json
[
    {
        "id": 1,
        "name": "Bulbasaur",
        "image": "images/bulbasaur.jpg"
    },
    {
        "id": 2,
        "name": "Ivysaur",
        "image": "images/ivysaur.jpg"
    },
    ...
]
```

### Get individual Pokémon details

We can get individual Pokémon details using the Pokémon id from the above list.

`https://arindampal-0.github.io/pokemon-api/pokemon/[id].json`

where `[id]` can be replaced by Pokémon id.

```json
{
  "id": 1,
  "name": "Bulbasaur",
  "image": "images/bulbasaur.jpg",
  "type": "grass",
  "height": "0.71 m",
  "weight": "6.9 kg",
  "abilities": "overgrow",
  "stats": {
    "hp": 45,
    "attack": 49,
    "defense": 49,
    "sp_atk": 65,
    "sp_def": 65,
    "speed": 45
  }
}
```

### get individual Pokémon image

`https://arindampal-0.github.io/pokemon-api/images/[image_url].jpg`

where `[image_url]` can be replaced by Pokémon image path.

Example:

`https://arindampal-0.github.io/pokemon-api/images/bulbasaur.jpg`

<br>

## Pokemon API used

The API data is provided by [Jack Herrington](https://github.com/jherr).

The API data can be found at [pokemon](https://github.com/jherr/pokemon).
