data delete
{}
lineage delete
## Concepts - Headers
Any documentation or the concepts used in the headers of your data table.
```
|    | name      | type   | description                                                          |
|---:|:----------|:-------|:---------------------------------------------------------------------|
|  0 | Date      | string | The data of the transactions                                         |
|  1 | Open      | float  | The price for a share when the market opens                          |
|  2 | High      | float  | The highest price for a share during the trading day                 |
|  3 | Low       | float  | The lowest price for a share during the trading day                  |
|  4 | Close     | float  | The closing price for a share at the end of the trading day          |
|  5 | Adj Close | float  | The adjusted closing price for a share at the end of the trading day |
|  6 | Volume    | int    | The amount of shares that were exchanged on the day                  |
```
## Concepts - Values
Any documentation or the concepts used in the values of acolumn in your data table.
```
| entity   | header name   | type   | description   |
|----------|---------------|--------|---------------|
```
## Meta
Any documentation of the metadata used to describe and discover your data.
```
|    | key           | value                                                                     |
|---:|:--------------|:--------------------------------------------------------------------------|
|  0 | contract      | Apple                                                                     |
|  1 | specification | https://github.com/JSON-UNIFY                                             |
|  2 | description   | The data contract for Apple's financial information from Yahoo Finance    |
|  3 | source        | https://raw.githubusercontent.com/JSON-UNIFY/Data-Contracts/main/AAPL.csv |
|  4 | table         |                                                                           |
|  5 | query         |                                                                           |
|  6 | tags          |                                                                           |
|  7 | authors       | Yahoo Finance                                                             |
|  8 | id            |                                                                           |
|  9 | contact       |                                                                           |
| 10 | name          | Trading data for Apple                                                    |
| 11 | markdown      |                                                                           |
| 12 | catalog       | https://github.com/JSON-UNIFY/Financial-Contract-Catalogs                 |
```
## Governance - SLA
Any documentation of any SLA information.
```
| category   | provider   | customer   | requirement   |
|------------|------------|------------|---------------|
```
## Lineage
Data lineage information
```
| command   | params   | date   |
|-----------|----------|--------|
```
## Data
The data of your JSON-Unify object.
```

```

## JSON-Unify Object (file)
This is the JavaScript Object Notation representation of your PyUnify Object. You could save this to a file and import it, use it in Javascript, etc.


```
{
    "concepts": {
        "headers": {
            "name": [
                "Date",
                "Open",
                "High",
                "Low",
                "Close",
                "Adj Close",
                "Volume"
            ],
            "type": [
                "string",
                "float",
                "float",
                "float",
                "float",
                "float",
                "int"
            ],
            "description": [
                "The data of the transactions",
                "The price for a share when the market opens",
                "The highest price for a share during the trading day",
                "The lowest price for a share during the trading day",
                "The closing price for a share at the end of the trading day",
                "The adjusted closing price for a share at the end of the trading day",
                "The amount of shares that were exchanged on the day"
            ]
        },
        "values": {
            "entity": [],
            "header name": [],
            "type": [],
            "description": []
        }
    },
    "data": {},
    "governance": {
        "sla": {
            "category": [],
            "provider": [],
            "customer": [],
            "requirement": []
        }
    },
    "lineage": {},
    "schema": {
        "$schema": "https://json-schema.org/draft/2020-12/schema",
        "$id": null,
        "title": null,
        "description": null,
        "type": "object",
        "properties": {}
    },
    "json-ld": [],
    "meta": {
        "key": [
            "contract",
            "specification",
            "description",
            "source",
            "table",
            "query",
            "tags",
            "authors",
            "id",
            "contact",
            "name",
            "markdown",
            "catalog"
        ],
        "value": [
            "Apple",
            "https://github.com/JSON-UNIFY",
            "The data contract for Apple's financial information from Yahoo Finance",
            "https://raw.githubusercontent.com/JSON-UNIFY/Data-Contracts/main/AAPL.csv",
            null,
            null,
            null,
            "Yahoo Finance",
            null,
            null,
            "Trading data for Apple",
            null,
            "https://github.com/JSON-UNIFY/Financial-Contract-Catalogs"
        ]
    }
}
```
## JSON-Unify Object (string)
Use this version to copy and paste into Jupyter Notebook to create a PyUnify Object


```
'{"concepts": {"headers": {"name": ["Date", "Open", "High", "Low", "Close", "Adj Close", "Volume"], "type": ["string", "float", "float", "float", "float", "float", "int"], "description": ["The data of the transactions", "The price for a share when the market opens", "The highest price for a share during the trading day", "The lowest price for a share during the trading day", "The closing price for a share at the end of the trading day", "The adjusted closing price for a share at the end of the trading day", "The amount of shares that were exchanged on the day"]}, "values": {"entity": [], "header name": [], "type": [], "description": []}}, "data": {}, "governance": {"sla": {"category": [], "provider": [], "customer": [], "requirement": []}}, "lineage": {}, "schema": {"$schema": "https://json-schema.org/draft/2020-12/schema", "$id": null, "title": null, "description": null, "type": "object", "properties": {}}, "json-ld": [], "meta": {"key": ["contract", "specification", "description", "source", "table", "query", "tags", "authors", "id", "contact", "name", "markdown", "catalog"], "value": ["Apple", "https://github.com/JSON-UNIFY", "The data contract for Apple\'s financial information from Yahoo Finance", "https://raw.githubusercontent.com/JSON-UNIFY/Data-Contracts/main/AAPL.csv", null, null, null, "Yahoo Finance", null, null, "Trading data for Apple", null, "https://github.com/JSON-UNIFY/Financial-Contract-Catalogs"]}}'
```
