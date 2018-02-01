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

### KEYWORD HELPER

Copy this to your bookmarks and use for keywords searching 

```js
javascript:(function()%7Bvar%20_thisVersion%20=%201.1;if(document.getElementById('mkhScriptFile')!=null)%7BMKH.run(true,%20_thisVersion);%7Delse%7Bvar%20_p='https://mkh.squiz.net/s/resources/squiz-manuals/_default/matrixKeywordHelper.js';var%20_i=function(s,cb)%7Bvar%20sc=document.createElement('script');sc.onload=function()%7Bsc.onload=null;sc.onreadystatechange=null;sc.id='mkhScriptFile';cb.call(this);%7D;sc.onreadystatechange=function()%7Bif(/%5E(complete%7Cloaded)%24/.test(this.readyState)===true)%7Bsc.onreadystatechange=null;sc.onload();%7D%7D;sc.src=s;if(document.head)%7Bdocument.head.appendChild(sc);%7Delse%7Bdocument.getElementsByTagName('head')%5B0%5D.appendChild(sc);%7D%7D;var%20options=%7Bpath:_p%7D;_i(_p+'',function()%7BMKH.run(false,%20_thisVersion);%7D);%7D%7D)();
```

## URL

`&SQ_PAINT_LAYOUT_NAME=<name>` - User defined paint layout

`&SQ_DESIGN_NAME=<name>` - User defined design

`<url>/_nocache` - Shows page without cache

`<url>/_recache` - Caches page again

`<url>/_edit` - Edit+ Mode

`<url>/_admin` - Admin Mode
