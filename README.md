# Restful-currency-conversion-API-with-full-CRUD-functionality
REST based micro-service that provides live “to” &amp; “from” conversions of requested currencies. 
With an additional client based application for testing purposes that incorporates CRUD.

## Good reponse examples:
Example of conversion in XML: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of conversion in JSON: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=json

## Error code response examples:
Example of incorrect request for response format: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=10.35&format=xml

Example of incorrect request for conversion value: https://kieranfarrer.co.uk/currencyapi/index.php?from=GBP&to=JPY&amnt=x&format=json

# CRUD client application
client based application allows the addition or removal of certain currencies from the service. Also allows client to update the currency rate file to the most recent rates for currencies that are currently "live".
