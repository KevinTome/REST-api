# REST-api
Building a fully functional REST API with Node.js, express and MongoDB

## Built with
- Express
- Nodemon
- Mongoose

## API Routes

### Subscribers

| Route               | Method | Description                          |
|---------------------|--------|--------------------------------------|
| /subscribers        | GET    | Get all subscribers from database    |
| /subscribers/:id    | GET    | Get one subscriber by name           |
| /subscribers        | POST   | Create one subscriber by id          |
| /subscribers/:id    | PATCH  | Update one subscriber by id          |
| /subscribers/:id    | DELETE | Delete one subscriber by id          |

### Model

| Name        | Number of Data | All Data                                 |
|-------------|----------------|------------------------------------------|
| subscriber  | 3              | name, subscribedToChannel,subscribeDate  |

