# SR
SR parameters
SR 2 parameters
SR 3 parameters
SR 4 parameters
SR 5 parameters
SR 6 parameters
SR 7 parameters
# surfreport/{beachId}
1
2
3
4
5
6
7
8
9
0
Return
Return 2
Return 3
Return 4
Return 5
Return 6
Return 7
Return 8

Returns information about surfing conditions at a specific beach ID, including the surf height, water temperature, wind, and tide. Also provides an overall recommendation about whether to go surfing.
Surfing.

`{beachId}` refers to the ID for the beach you want to look up. All Beach ID codes are available from our site.

## Endpoint definition

`surfreport/{beachId}`

## HTTP method

<span class="label label-primary">GET</span>

## Parameters

| Parameter | Description | Data Type |
|-----------|------|----------|
| days | *Optional*. The number of days to include in the response. Default is 3. | integer |
| time | *Optional*. If you include the time, then only the current hour will be returned in the response.| integer. Unix format (ms since 1970) in UTC. |

## Sample request
