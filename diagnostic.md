# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
data persistence
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model
```

Which layer in the MVC pattern communicates with the model?

```bash
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We are using Rails solely for API purposes. We will use javascript for front end parts of our applications.
```

What does C.R.U.D stand for?

```bash
CREATE, READ, UPDATE, DELETE
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Routes
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
POST, GET, PATCH, PUT, DELETE
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
- Client makes HTTP request to server
- Server finds controller and gives request information
- Controller communicates with model if all information needed is correct
- Model interacts with database to find information.
- Model returns information to controller
- Controller sends info back to Server
- Server sends info back to client
```

What is the command to generate a new rails-api app?

```bash
rails-api new app_name
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
- bundle exec rake db:drop
- bundle exec rake db:create
- bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bundle exec rails-api g scaffold pet name:string age:integer
```
