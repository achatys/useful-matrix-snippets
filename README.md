# Useful Matrix Snippets

## REST

`_REST.responses[0].body` - Prints the body of response in REST asset

`_REST.request.urls[0]` - Prints the url of request

`%globals_server_QUERY_STRING%` - Prints parameters from url

`%globals_get_<name>%` - Prints specific parameter from url

## KEYWORDS

`%asset_position^eq:1::,%` - First item without comma at the beginning (useful in asset listings)

`%asset_contents_paint_<id>%` - Use for nesting paint layout
