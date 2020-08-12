# Workshop Description: Infrastructure for a Fraud Detection ML Application

This is the accompanying repo for a hands on workshop for building a ML infrastructure based on a real life system used in production.

The architecture is based on the PayPal fraud detection infrastructure and is designed for the conference attendees to have a hands on experience of a ML infrastructure.

The workshop was given at the [Go Get conference](https://www.gogetcommunity.com/) in 05/2020 and will be given again at [GopherCon](https://www.gophercon.com/) in 11/2020. 

The workshop is created by [Natalie Pistunovich](https://twitter.com/nataliepis). 

# Setup

- Have [GitHub](https://help.github.com/en/github/getting-started-with-github/set-up-git) set up on your machine
- Clone this repo
- Install [Go](https://golang.org/dl/) (v1.14)
- Install the latest [Docker](https://docs.docker.com/get-docker/)
- Pull the Docker images:
  - docker pull aerospike/aerospike-server:5.0.0.10
  - docker pull aerospike/aerospike-tools:3.28.0
  - docker pull tensorflow/serving:2.2.0
- Download the [Kaggle dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud/data) of credit card transactions 


In case you are new to Go, here are some useful links:
- A summarized overview of Go: [Learn Go in Y Minutes](https://learnxinyminutes.com/docs/go/)
- A short hands on tutorial: [Tour of Go](http://tour.golang.org/) 
- A handy cheatsheet: [Go by Example](https://gobyexample.com/)
