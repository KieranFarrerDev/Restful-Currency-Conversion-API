# Restful-currency-conversion-API-with-full-CRUD-functionality
REST based micro-service that provides live “to” &amp; “from” conversions of requested currencies.

Features an additional client based CRUD application "update.php" that allows the addition or removal of currencies from the service. The application also allows the client to update thier currency file by making calls to the currency rates service provider, ammending the currencies to their most recent rates.

## Good reponse examples:
Example of conversion in XML request: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of conversion in JSON request: https://kieranfarrer.co.uk/currencyapi/index.php?from=USD&to=CNY&amnt=250&format=json

## Error code response examples:
Example of incorrect response format request: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of incorrect conversion value request: https://kieranfarrer.co.uk/currencyapi/index.php?from=USD&to=CBY&amnt=x&format=json

