# SR P
SR parameters
# surfreport/{beachId}

Returns all the information about surfing conditions at a specific beach ID, including the surf height, water temperature, wind, and tide. Also provides an overall recommendation about whether to go surfing.

`{beachId}` refers to the ID for the beach you want to look up. All Beach ID codes are available from our site.

## Endpoint definitions

`surfreport/{beachId}`

## HTTP method

<span class="label label-primary">GET</span>

## Parameters

| Parameter | Description | Data Type |
|-----------|------|----------|
| days | *Optional*. The number of days to include in the response. Default is 3. | integer |
| time | *Optional*. If you include the time, then only the current hour will be returned in the response.| integer. Unix format (ms since 1970) in UTC. |

## Sample request
