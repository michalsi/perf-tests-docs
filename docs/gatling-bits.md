## Check if a HTML result contains some string

with one single CSS selector:

```.check(css("h1:contains('Access denied')").notExists)```

with substring:

```.check(substring("Access denied").notExists)```

Note: if what you're looking for only occurs at one place in your response payload, substring is sure more efficient, as it doesn't have to parse it into a DOM.

source: _https://stackoverflow.com/a/35717805_

## Check status
By default Gatling performs following check:

``` status.find.in(200,201,202,203,204,205,206,207,208,209,304), found 404```
