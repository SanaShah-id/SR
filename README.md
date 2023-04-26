# SR
SR parameters
SR 2 parameters 2 2 2
SR 3 parameters 3 3 3
SR 4 parameters 4 4 4
SR 5 parameters 5 5 5
SR 6 parameters 6 6 6
SR 7 parameters 7 7 7
# surfreport/{beachId}
1 1 1
2 2 2
3 3 3
4 4 4
5 5 5
6 6 6
7 7 7
8 8 8
9 9 9
0 0 0
Return
Return 2 2 2
Return 3 3 3
Return 4 4 4
Return 5 5 5
Return 6 6 6
Return 7 7 7
Return 8 8 8

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
