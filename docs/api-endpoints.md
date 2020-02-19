## API Endpoints

### HTML API
#### root
* GET / - loads home

### JSON API
#### users
* GET /search - returns the user information for the User Search feature
* POST /signup - sign up

#### sessions
* POST /api/session 
* DELETE api/session 

#### songs
* GET /api/songs - index
* GET /api/songs/:id - show
* POST /api/songs - index
* PATCH /api/songs/:id - update
* DELETE /api/:id - destroy

#### comments
* GET /api/songs/:id/comments - show all comments on song
* POST /api/comments - create comment on song
* PATCH /api/comments - update
* DELETE /api/comments/:id - destroy
