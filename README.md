# udemy-golang-microservices

Following Udemy course "Golang Microservices: Breaking a Monolith to Microservices".

# Getting the applications started

## Setting up the application:

### App: go-ambassador

1. `docker-compose up`
2. `docker-compose exec backend sh`
3. `cd src/commands`
4. `go run populateUsers.go`
4. `go run populateOrders.go`
4. `go run populateProducts.go`

### App: react-ambassador

1. react-admin
  1. `npm i`
2. react-ambassador
  1. `npm i`
3. next-checkout
  1. `npm i`

## Running the application:

### App: go-ambassador:

1. TODO

1. react-admin
  1. `npm start`
  2. First time set-up: Go to http://localhost:3000/register to create a new user. Use `a` for all entries except email, which will be `a@a.com`.
  2. Go to http://localhost:3000/login
  3. Log with `a` user.
2. react-ambassador
  1. `npm start` - note that there is a typo in the course. So, update the **package.json** file and update the `start` command to `set PORT=4000 && react-scripts start`.
  2. Go to http://localhost:4000/
  3. Sign up new user. Use `b` for all entries except email, which will be `b@b.com`.
  4. Select a product.
  5. Click *Generate a link*.
  6. Copy the link into a new browser, which will take you to the Checkout app.
3. next-checkout
  1. `npm run dev`
  2. Go to http://localhost:5000
