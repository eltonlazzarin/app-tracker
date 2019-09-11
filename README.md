Exercise Tracker REST API
=========================

Three REST services,

Create a New User
- POST /api/exercise/new-user

Add exercises
- POST /api/exercise/add

GET Users's exercise log
- GET /api/exercise/log?{userId}[&from][&to][&limit]

  { } = required, [ ] = optional
  from, to = dates (yyyy-mm-dd); limit = number

