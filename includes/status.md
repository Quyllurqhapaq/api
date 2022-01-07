=== "Status: 429 :red_circle:"
    **Response type:** json
    ```
    {
        "error": "429 Too Many Requests",
        "description": "This user has exceeded an allotted request count. Try again later."
    }
    ```

=== "Status: 404 :red_circle:"
    **Response type:** json
    ```
    {
        "error": "404 Not Found",
        "description": "The requested URL was not found on the server. Please check that URL and try again."
    }
    ```

=== "Status: 500 :red_circle:"
    **Response type:** json
    ```
    {
        "error": "500 Internal Server Error",
        "description": "Sorry, the server encountered an internal error and was unable to complete your request. Please try again later."
    }
    ```