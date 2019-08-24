# Local development environment 
Launch a full stack dev environment for api, webapp and database using docker-compose

## Instructions
1. Install [Docker](https://docs.docker.com/install/)
2. Checkout both [api](https://github.com/teleportlabs/api) and [webapp](https://github.com/teleportlabs/webapp) projects
3. Create a `.env` file. Copy the content of `.env.example` into it and adjust it to your local environment.
4. Open Terminal and `cd` to `api-webapp` folder
5. run `docker-compose up`
6. All set!. Server can be reached at 'http://locahost:4000', mongo at 'http://localhost:27017' and webapp at 'http://locahost:3000' (check `.env.example` for DB credentials)
