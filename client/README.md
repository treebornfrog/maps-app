#Leaflet Codde Along with CJ

# Guest Map

- App detects users location (from browser or IP)
- Guests of the website can leave a message
- A pin will be added to the map with the users location and message

## TODO

- [x] create-react-app
- [x] Install react-leaflet: https://github.com/PaulLeCam/react-leaflet
- [x] Get a map on the page!
- [x] Get the users location
  - [x] with the browser
  - [x] with their IP using an API
- [x] Show a pin at the users location
- [x] Show a form to submit a message
  - when form is submitted - POST /message
- [x] Setup server with create-express-api: https://www.npmjs.com/package/create-express-api
- [x] Add monk and joi
- [] POST /messages
  - latitude
  - longitude
  - name
  - message
  - datetime
- [] When the page loads get all messages
  - [] GET /messages
- [] Add pins to the map
- [] Click a pin to see the message
- [] DEPLOY!
  - [] https://guestm.app
- Refactor React app
  - seperate components
  - seperate file for API requests
  - seperate file for Location requests

## Stretch

- [ ] Allow user to drag pin
- [ ] Login
- [ ] Users have their own guest map with their own markers and unique URL
