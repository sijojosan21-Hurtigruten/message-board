# message-board

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

<br/>

Application can be accessed at [sijojosan.com]

<br/>

### Technology Stack
  - Spring Boot/Java - for the backend REST API endpoints
  - Reactjs - for the frontend UI
  - PostgreSQL - for data persistence
  - Docker - for containerization
  - [Travis CI] - for build and deployment
  - Amazon Web Services - for hosting
<br/>

### What is Travis CI
Travis CI is a hosted continuous integration service used to build and test software projects hosted at GitHub and Bitbucket. Travis CI provides various paid plan for private projects, and a free plan for open source.
<br/>

### How to Deploy in AWS
  - Commit changes to the develop branch.
  - Create a pull request to the master branch.
  - Merge the pull request.
  - Changes will be automatically detected and deployed to AWS with the help of Travis CI. (refer .travis.yml)
<br/>

### How to Deploy in Local
Make the required changes in either the UI or the service backend and run the flowing commands. ([Docker Desktop] is required)
```sh
cd message-board
docker-compose build
docker-compose up
```
<br/>

### System Architecture 
![System Architecture](/misc/arch.jpg)


### Docker Container Components
![Docker Container Components](/misc/cont.jpg)


### Deployment Overview
![Deployment Overview](/misc/dplymnt.jpg)


[sijojosan.com]: <http://sijojosan.com>
[Travis CI]: <https://travis-ci.org>
[Docker Desktop]: <https://www.docker.com/products/docker-desktop>
