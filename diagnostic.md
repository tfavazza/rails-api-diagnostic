# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
to hold database information. to give the opportunity for a webapp to be
interactive across computers.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model layer
```

Which layer in the MVC pattern communicates with the model?

```bash
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// your response here
```

What does C.R.U.D stand for?

```bash
CREATE
READ
UPDATE
DELETE
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
controller
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
for SQL / HTTP / Ruby
CREATE - insert / post / create
READ - select / get / index/show
UPDATE - update / patch / update
DELETE - delete / delete / destroy

```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. GET request sent to routes
2. routes points to appropriate controller
3. controller talks to appropriate model
4. model sends back information to controller
5. controller gives this back to the front end
```

What is the command to generate a new rails-api app?

```bash
rails-api new blog_app --skip-javascript --skip-sprockets --skip-turbolinks --skip-test-unit --database=postgresql
```

What is the command to start an instance of a rails server?

```bash
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rails db:drop
rails db:create
rails db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pet name:string age:string
```

List two advantages of using serializers? (2 bullet points)

```bash
safer
easier to use
```
