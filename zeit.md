### zeit

all you need to do

- `now --prod` (automatically will detect that you are using create-react-app, and
  will build it on their server... you don't have to run "npm run build")

### api

- anything in the "api" folder will get deployed as a
  "zeit serverless function" in the cloud. You can use any
  programming lnaguage
- "api/index.js" can access by doing --> `fetch('/api')`
- "api/weather.js" can access by doing --> `fetch('/api/weather')`

- the syntax for javascript serverless functions:

```js
module.exports = async function(req, res) {
  try {
    // do something

    // req.body = body of the request (for POST)
    // ^ usually used for creating a new data (i.e. like a new friend)
    // req.query = guery parameters (?lat=1.2&lng=2)
    // ^ usually used for GET request
    res.status(200).send(response);
  } catch (e) {
    res.status(500).send(e.message);
  }
};
```

- any language can be used on zeit
- they cannot handle websockets
