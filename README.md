<p align="center">
  <a href="https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/wiki">
    <img src="https://raw.githubusercontent.com/wiki/fga-gpp-mds/Falko-2017.2-BackEnd/images/logo.png" width=150 height=150>
  </a>

  <h3 align="center">Falko</h3>

  <p align="center">
    <i>Veja além</i>
    <br>
    <a href="https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/wiki"><strong>Visite nossa Wiki &raquo;</strong></a>
    <br>
    <br>
    <a href="http://falko.solutions">Access Falko</a>
    &middot;
    <a href="https://github.com/fga-gpp-mds/Falko-2017.2-FrontEnd">FrontEnd Repository</a>
    &middot;
    <a href="https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/issues">Report an Issue</a>
  </p>
</p>

<p align="center">
  <a href="https://codeclimate.com/github/fga-gpp-mds/Falko-2017.2-BackEnd"><img src="https://codeclimate.com/github/fga-gpp-mds/Falko-2017.2-BackEnd/badges/gpa.svg" alt="Code Climate GPA"></a>
  <a href="https://codeclimate.com/github/fga-gpp-mds/Falko-2017.2-BackEnd"><img src="https://codeclimate.com/github/fga-gpp-mds/Falko-2017.2-BackEnd/badges/coverage.svg" alt="Code Climate Coverage"></a>
  <a href="https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd" alt="Travis Build"><img src="https://img.shields.io/travis/fga-gpp-mds/Falko-2017.2-BackEnd.svg"></a>
  <a href="https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd"><img src="https://img.shields.io/github/license/fga-gpp-mds/Falko-2017.2-BackEnd.svg" alt="License"></a>
  <a href="https://img.shields.io/badge/GPP%2FMDS-2017.2-brightgreen.svg"><img src="https://img.shields.io/badge/GPP%2FMDS-2017.2-brightgreen.svg" alt="GPP/MDS"></a>
</p>

<br></br>

## Introduction

Falko is an web application, developed using Ruby on Rails API and Vue.js. It is a Freen Software Project, developed initially to GPP/MDS subjects of UnB - University of Brasília - Engeneering Campus (FGA). Falko aims to promote a platform that makes easier for managers _to manage_ agile projects through displaying metrics and relevant info regarding the project, also contributing to more eficient decision making.

## Development setup

Development environment uses the containers architecture through _Docker_. To install, simply follow the guide [How to Use Docker](https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/wiki/How-to-Use-Docker).
If you're not familiar with docker, you can just simplify some default commands with _make_.

### *_Make_ usage*
#### Enters the Rails Console
`$ make console`

#### Creates the development and test database
`$ make create-db`

#### Drops down the docker environment
`$ make down`

#### Migrates the Rails database
`$ make migrate`

#### Lists all your running services
`$ make ps`

#### Removes all your docker networks
`$ make rm-network`

#### Removes all your docker mapped volumes
`$ make rm-volume`

#### Creates the Falko environment and run it
`$ make run`

#### Creates the Falko environment and run it as daemon
`$ make quiet-run`

#### Creates only the API environment, without database service
`$ make run-api`

#### Creates only the Postgres database environment, without API service
`$ make run-db`

#### Seeds the Rails database environment
`$ make seed`

#### Executes all of Rails' tests
`$ make test`

## Documentation

Additional documentation is avaiable at [Official Wiki](https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/wiki).

## How to Contribute

To contribute with us, the colaborator must _fork_ and send a [pull request](https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/pulls) with his/her contribution to _devel_ branch.
The code will be analized by one of the project's owners and, if approved, included to the application's core.

## License

[MIT](https://github.com/fga-gpp-mds/Falko-2017.2-BackEnd/blob/devel/LICENSE)

Copyright (c) 2017 Falko Organization
