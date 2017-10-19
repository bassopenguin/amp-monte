# amp-monte
An exploration of AMP and other web technologies

## Setup
- Configure a JSON endpoint providing an array inside "items"

_Example [json-server](https://www.npmjs.com/package/json-server) endpoint:_
```json
{
    "endpoint": {
        "items": [
            {
                "username": "username",
                "total_value": "$11,525.70",
                "securities": [
                    {
                        "symbol": "AAPL",
                        "quantity": 10,
                        "price": "$159.76",
                        "equity": "$1,597.60"
                    },
                    {
                        "symbol": "GOOG",
                        "quantity": 10,
                        "price": "$992.81",
                        "equity": "$9,928.10"
                    }
                ],
                "watchlist": [
                    {
                        "symbol": "FB",
                        "price": "$176.03"
                    },
                    {
                        "symbol": "SNAP",
                        "price": "$15.75"
                    }
                ]
            }
        ]
    }
}
```

_NOTE: If not using a json-server endpoint, update `amp-list src` tags in index.html_