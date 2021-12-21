---
title: Tea API
description: Tea API
---

## Tea

!!! example "**Tea**"

    ### **Endpoint information**
    - **Endpoint:** [https://api.zarena.ga/v1/tea](https://api.zarena.ga/v1/tea) <br>
    - **Method:** GET <br>

    ### **Response**
    === "Status: 200 :green_circle:"
        **Response type:** json
        ```
        {
            "url": "https://cdn.zarena.ga/image/tea/tea_1.jpg"
        }
        ```

    === "Status: 404 :red_circle:"
        **Response type:** json
        ```
        {
            "error": "The resource could not be found."
        }
        ```
