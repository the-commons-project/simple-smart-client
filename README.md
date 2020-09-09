# Simple SMART Client

Based on [this tutorial](http://docs.smarthealthit.org/tutorials/javascript/)

To run locally, you can use any development HTTP server and point it to this directory. For example:

```
python -m http.server 9000
```

Then, open `http://localhost:9000/launch.html` in your browser.

Currently, it points to the SMART IT DSTU2 Sandbox. To point to another SMART on FHIR server, modify the `iss` parameter in `launch.html`. Note that you may also need to modify the clientId and clientSecret parameters as well.

