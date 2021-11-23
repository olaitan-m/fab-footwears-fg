## Project Description

A minimal e-commerce web app built with Vue.js and Express node.js server

## Demo

https://fab-footwears-fg.herokuapp.com/

## Tools and Packages

### Frontend / Client

| Name                 | Description                                                                                                            |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| axios     | Promise based HTTP client for making request     |
| core-js     | ...     |

### Backend / Server

| Name                  | Description                                                                     |
| --------------------- | ------------------------------------------------------------------------------- |

| @babel/...     | Fontawesome icons     |
| body-parser     | Fontawesome icons     |
| connect-history-api-fallback     | Fontawesome icons     |

## Functionalities

- 

## Local Setup

1. install node@14.17
1. install mongodb 5.0.3
1. Clone Repo
1. `npm install`
1. `cd client && npm install`
1. start mongodb service</br>
   `brew services start mongodb-community@5.0` </br>
   From terminal `mongosh`
1. setup fake-data `use fab-footwears-db` `db.products.insertMany([])` `db.  ``db.users.insertOne({id: '001', cartItems: ['001', '002', '003']})``
1. Test in browser
1. Stop mongodb service </br>
   `brew services stop mongodb-community@5.0`

## Production Setup

1. `git init`
1. `heroku login`
1. `heroku create [APP_NAME]`
1. `heroku git:remote -a [APP_NAME]`
1. confirm/setup environment variables in heroku. </br>
1. `cd client && npm install`
1. `git push heroku master`
1. `heroku open`
1. add some initial data to the cloud database mongodb atlas.
1. Test in browser
1. check logs `heroku logs --tail`

## Troubleshooting


