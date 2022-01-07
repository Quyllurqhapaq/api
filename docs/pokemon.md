---
title: Pokemon API
description: Pokemon API
---

Get Pokemon info and their stats upto generation 8!

## Search by ID

!!! example "**Pokemon**"

    ### **Endpoint information**
    - **Endpoint:** [https://api.zarena.ga/v1/pokemon?id=1](https://api.zarena.ga/v1/pokemon?id=1) <br>
    - **Method:** GET <br>

    ### **Response**
    === "Status: 200 :green_circle:"
        **Response type:** json
        ```
        {
            "id": "1",
            "name": "bulbasaur",
            "species": "Seed",
            "type": [
                "Grass",
                "Poison"
            ],
            "abilities": [
                "Overgrow",
                "Chlorophyll"
            ],
            "height": "0.7 m (2′04″)",
            "weight": "6.9 kg (15.2 lbs)",
            "gender": "87.5% male, 12.5% female",
            "description": "A strange seed was planted on its back at birth. The plant sprouts and grows with this Pokemon.",
            "base_experience": "64",
            "generation": "1",
            "effort_value": "1 Special Attack",
            "catch_rate": "45",
            "base_friendship": "50",
            "growth_rate": "Medium Slow",
            "forms": "None",
            "legendary": "False",
            "mythical": "False",
            "ultra_beast": "False",
            "mega": "False",
            "gigantamax": "False",
            "egg_cycles": "20 (4,884–5,140 steps)",
            "egg_groups": [
                "Grass",
                "Monster"
            ],
            "weakness": [
                "Fire",
                "Psychic",
                "Flying",
                "Ice"
            ],
            "stats": {
                "hp": "45",
                "attack": "49",
                "defense": "49",
                "sp_atk": "65",
                "sp_def": "65",
                "speed": "45",
                "total": "318"
            },
            "family": {
                "evolutionStage": 1,
                "evolutionLine": [
                    "Bulbasaur",
                    "Ivysaur",
                    "Venusaur"
                ]
            },
            "sprites": {
                "normal": "https://assets.pokemon.com/assets/cms2/img/pokedex/full/001.png",
                "animated": "https://img.pokemondb.net/sprites/black-white/anim/normal/bulbasaur.gif",
                "shiny": "https://assets.poketwo.net/shiny/1.png",
                "normal2": "https://img.pokemondb.net/sprites/home/normal/bulbasaur.png",
                "shiny2": "https://img.pokemondb.net/sprites/home/shiny/bulbasaur.png"
                }
            }
        ```

    --8<-- "includes/status.md"

## Search by name

!!! example "**Pokemon**"

    ### **Endpoint information**
    - **Endpoint:** [https://api.zarena.ga/v1/pokemon?name=bulbasaur](https://api.zarena.ga/v1/pokemon?name=bulbasaur) <br>
    - **Method:** GET <br>

    ### **Response**
    === "Status: 200 :green_circle:"
        **Response type:** json
        ```
        {
            "id": "1",
            "name": "bulbasaur",
            "species": "Seed",
            "type": [
                "Grass",
                "Poison"
            ],
            "abilities": [
                "Overgrow",
                "Chlorophyll"
            ],
            "height": "0.7 m (2′04″)",
            "weight": "6.9 kg (15.2 lbs)",
            "gender": "87.5% male, 12.5% female",
            "description": "A strange seed was planted on its back at birth. The plant sprouts and grows with this Pokemon.",
            "base_experience": "64",
            "generation": "1",
            "effort_value": "1 Special Attack",
            "catch_rate": "45",
            "base_friendship": "50",
            "growth_rate": "Medium Slow",
            "forms": "None",
            "legendary": "False",
            "mythical": "False",
            "ultra_beast": "False",
            "mega": "False",
            "gigantamax": "False",
            "egg_cycles": "20 (4,884–5,140 steps)",
            "egg_groups": [
                "Grass",
                "Monster"
            ],
            "weakness": [
                "Fire",
                "Psychic",
                "Flying",
                "Ice"
            ],
            "stats": {
                "hp": "45",
                "attack": "49",
                "defense": "49",
                "sp_atk": "65",
                "sp_def": "65",
                "speed": "45",
                "total": "318"
            },
            "family": {
                "evolutionStage": 1,
                "evolutionLine": [
                    "Bulbasaur",
                    "Ivysaur",
                    "Venusaur"
                ]
            },
            "sprites": {
                "normal": "https://assets.pokemon.com/assets/cms2/img/pokedex/full/001.png",
                "animated": "https://img.pokemondb.net/sprites/black-white/anim/normal/bulbasaur.gif",
                "shiny": "https://assets.poketwo.net/shiny/1.png",
                "normal2": "https://img.pokemondb.net/sprites/home/normal/bulbasaur.png",
                "shiny2": "https://img.pokemondb.net/sprites/home/shiny/bulbasaur.png"
                }
            }
        ```

    --8<-- "includes/status.md"
