# Protocol
BR-UTM's Strategic Coordination and Restriction Protocol

## Viewing locally
To view this YAML file locally:

```shell script
docker run -it --rm -p 8080:8080 \
  -v $(pwd)/:/usr/share/nginx/html/api/ \
  -e PORT=8080 -e SPEC_URL=api/utm.yaml redocly/redoc
```

...then visit [http://localhost:8080/](http://localhost:8080/) in a browser.
