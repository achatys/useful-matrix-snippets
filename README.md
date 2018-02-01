# Useful Matrix Snippets

## REST

`_REST.responses[0].body` - Prints the body of response in REST asset

`_REST.request.urls[0]` - Prints the url of request

`%globals_server_QUERY_STRING%` - Prints parameters from url

`%globals_get_<name>%` - Prints specific parameter from url

## KEYWORDS

`%asset_position^eq:1::,%` - First item without comma at the beginning (useful in asset listings)

`%asset_contents_paint_<id>%` - Use for nesting paint layout

`%asset_data%` - Prints all information about asset

`%globals_site_metadata_<name>%` - Site related metadata

## URL

`&SQ_PAINT_LAYOUT_NAME=<name>` - User defined paint layout

`&SQ_DESIGN_NAME=<name>` - User defined design

`<url>/_nocache` - Shows page without cache

`<url>/_recache` - Caches page again

`<url>/_edit` - Edit+ Mode

`<url>/_admin` - Admin Mode
