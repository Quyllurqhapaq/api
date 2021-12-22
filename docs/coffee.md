---
title: Coffee API
description: Coffee API
---

An API for coffee lovers <3  
Get random coffee images.

## Coffee

!!! example "**Coffee**"

    ### **Endpoint information**
    - **Endpoint:** [https://api.zarena.ga/v1/coffee/random](https://api.zarena.ga/v1/coffee/random) <br>
    - **Method:** GET <br>

    ### **Response**
    === "Status: 200 :green_circle:"
        **Response type:** json
        ```
        {
            "url": "https://cdn.zarena.ga/image/coffee/coffee_4194.jpg"
        }
        ```

    === "Status: 404 :red_circle:"
        **Response type:** json
        ```
        {
            "error": "The resource could not be found."
        }
        ```
