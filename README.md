# Udagram

The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### AWS Cloud Setup

- RDS - Database Host: `postgres.cybxu07myc9a.us-east-1.rds.amazonaws.com`
- RDS - Database Port: 5432
- RDS - Database Name: postgres

- S3 Endpoint - Frontend: `http://udagram-omar1020.s3-website-us-east-1.amazonaws.com`

- Elastic Beanstalk URL - Backend: `http://udagram-api-dev.eba-922mbvda.us-east-1.elasticbeanstalk.com`


### Installation

Provision the necessary AWS services needed for running the application:

### circle ci pipeline status
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/omarabdelaziz10/udagram/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/omarabdelaziz10/udagram/tree/master)

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
