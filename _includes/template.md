# Citybreak Online Template Page Instructions

Citybreak Online enables customization by offering the possibility to include a template page for header and footer. The template page is provided by setting an absolute URL to an HTML page containing a placeholder element where the Citybreak Online booking engine will be injected. This gives the user ability to use their own header and footer as well as other static resources such as style sheets and JavaScripts. 

A responsive template page is strongly recommended.

[add image]

## Example

```html
curl -X GET 
  --header 'ApiKey: APIKEY132456789EWOK'
  --header 'Accept: application/json' 
  --header 'Accept-Language: en-US'
  'https://example.citybreak.com/v1/example'
```

```javascript
var r = fetch("https://example.citybreak.com/v1/example",
{
  headers: {
    "ApiKey:" "APIKEY132456789EWOK",
    "Accept": "application/json",
	"Accept-Language": "en-US"
  }  
});
```

> Example of response:

```json
{
  "Examples": [
	"Hello World test",
	"Ewoks are the best"
  ]
}
```

An example.

### HTTP Request

`POST https://example.citybreak.com/v1/example`

### Query Parameters

Parameter | Type |Description
--------- | ------ | -----------
Accept-Language | Header | The language.

