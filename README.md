# Examples

## Languages and Frameworks

* [Node.js - Let's Chat](https://github.com/codefreshdemo/demochat) - Use this tutorial to familiarize yourself with codefresh.yml file and codefresh functionality.
* [Golang - Prest](https://github.com/codefreshdemo/cf-example-golang-hello-world) - pREST allows you to serve a RESTful API from any PostgreSQL database.
* [Node.js - Voting App](https://github.com/containers101/voting-app) - This voting application is a demo with which you can build an advanced composition that uses Python, Redis, Postgres, Node.js, and .Net.
* [React - React starter kit](https://github.com/containers101/react-starter-kit) - React Starter Kit is an opinionated boilerplate for web development built on top of Node.js, Express, GraphQL and React, containing modern web development tools such as Webpack, Babel and Browsersync.
* [Java - Spring MVC](https://github.com/codefreshdemo/cf-example-java-hello-world) - This project uses JAVA, SpringMVC, Tomcat, MySQL, Maven to build an application which will eventually become a distributable Docker image.
* [Python - Djanga](https://github.com/codefreshdemo/cf-example-python-djanga) - This project uses Python and Django to build an application which will eventually become a distributable Docker image.
* [Scala - Scala:Hello world](https://github.com/codefreshdemo/cf-example-scala-hello-world) - This project uses Scala to build an application which will eventually become a distributable Docker image and help you get up to speed with basic functionality such as: compiling, building Docker images and launching.
* [Protractor - Selenium test](https://github.com/codefreshdemo/cf-example-selenium-test) - This project uses JavaScript, Selenium, Protractor to build an application which will eventually become a distributable Docker image.

## Step Types and Techniques

* [Build an Image with the Dockerfile in Root Directory](https://docs.codefresh.io/docs/build-an-image-dockerfile-in-root-directory) - build step when Dockerfile is in root directory of repository.
* [Build an Image - Specify Dockerfile Location](https://docs.codefresh.io/docs/build-an-image-specify-dockerfile-location) - the build step with special Dockerfile location and path to build context.
* [Build an Image from a Different Git Repository](https://docs.codefresh.io/docs/build-an-image-from-a-different-git-repository) - contains the build and git-clone steps to show how to build the different git repository.
* [Build and Push an Image](https://docs.codefresh.io/docs/build-and-push-an-image) - in this example you will find how to use push step.
* [Build an Image with Build Arguments](https://docs.codefresh.io/docs/build-an-image-with-build-arguments) - using this repository we'll help you get up to speed with basic functionality such as: building Docker images with build arguments.
* [Run Unit Tests](https://docs.codefresh.io/docs/run-unit-tests) - running unit tests using freestyle step.
* [Run Unit Tests with composition](https://docs.codefresh.io/docs/run-unit-tests-with-composition) - running unit tests with composition using the composition step.
* [Run Integration Tests](https://docs.codefresh.io/docs/run-integration-tests) - running integration tests using the composition step.
* [Shared volumes of service from composition step for other yml steps](https://docs.codefresh.io/docs/shared-volumes-of-service-from-composition-step-for-other-yml-steps) - If you want to share volumes of service in composition step for other yml steps you can use the variable ${{CF_VOLUME}}. It will refer to the volume that was generated for the specific flow. Can be used in conjunction with a composition to provide access to your cloned repository.
* [Shared volumes between builds](https://docs.codefresh.io/docs/shared-volumes-between-builds) - If you want to save something data in shared volume you can do it using freestyle step. You will be able to get access to this volume in another build.
* [Launch Composition](https://docs.codefresh.io/docs/launch-composition-1) - launch environment using launch-composition step.
* [Clone private repository using freestyle step](https://docs.codefresh.io/docs/git-clone-private-repository-using-freestyle-step) - This project uses Node Js to build an application which will eventually become a distributable Docker image. If you want to extend the step git-clone you can use the freestyle step.
* [Push Image to an AWS EC2 Container Registry](https://docs.codefresh.io/docs/push-your-image-to-aws-registry)

## Useful compositions

* [Web terminal](https://docs.codefresh.io/docs/web-terminal) - Provides easy access to Docker container's insides.
* [Import data to MongoDB](https://docs.codefresh.io/docs/import-data-to-mongodb-in-composition) - If you want to import/restore or to do something else before using mongo db in your application you can look at the this example.
* [NodeJS + Angular2 + MongoDB](https://docs.codefresh.io/docs/nodejs-angular2-mongodb) - This tutorial will walk you through the process of adding the following: Build client, Build server, Launch composition.
* [Secure a Docker Container Using HTTP Basic Auth](https://docs.codefresh.io/docs/securing-docker-container-with-http-basic-auth) - Before making a product publicly available, you might want to restrict access to certain users.
* [List of useful compositions](https://github.com/codefresh-io/composition-examples/tree/master/compositions)

## Deployment

* [Amazon ECS](https://docs.codefresh.io/docs/amazon-ecs) - Deploy Codefresh to Amazon ECS Service
* [Docker SWARM](https://docs.codefresh.io/docs/docker-swarm) - Deploy to docker swarm
* [Elastic Beanstalk](https://docs.codefresh.io/docs/elastic-beanstalk) - Deploy to EB

## Codefresh command line

The Codefresh command line is a Dockerhub image, @codefresh-io/cf-cli, that you can use in your freestyle step. The Codefresh command line allows:

1. Trigger a pipeline
2. Launch a composition
3. Terminate/start/pause environment
4. Get list of images
5. Get list of builds
6. Get any other information from your codefresh.yml

* [How to trigger the another pipeline](https://docs.codefresh.io/docs/how-to-trigger-another-pipeline-using-cf-cli) - In this article you will find how to trigger the default/certain pipeline with default/certain branch of repository.
* [How to run composition](https://docs.codefresh.io/docs/how-to-run-composition-using-cf-cli-1)
* [How to spin up image](https://docs.codefresh.io/docs/how-to-spin-up-image-using-cf-cli)
