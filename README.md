# Restful-currency-conversion-API-with-full-CRUD-functionality
REST based micro-service that provides live “to” &amp; “from” conversions of requested currencies that features an additional client based CRUD application that allows the addition or removal of currencies from the service. The application also allows the client to update thier currency file by making calls to the currency rates service provider, ammending the currencies to their most recent rates.

## Good reponse examples:
Example of conversion in XML: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of conversion in JSON: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=json

## Error code response examples:
Example of incorrect request for response format: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of incorrect request for conversion value: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=x&format=json

