# Atelier Reviews API

## Summary

This is a clone of the '/reviews' and '/reviews/metas' endpoints being accessed in the Elm Catwalk eCommerce website repository to render front-end data, originally supplied via Heroku.  It has been load tested locally for performance via the included YML file in Artillery.  The provided scenarios revealed the capability of the API to run locally at a rate of 172 requests per second, at an average latency of 7 ms per request.  These results may vary depending upon active processes and hardware of the local machine upon forking and download.

## Installation

Run ```npm install``` in the desired location after forking and cloning the repo to the desired location.

## Dependencies
  - Axios: Version 0.26.1,
  - Express: Version 4.17.3,
  - MongoDB: Version 4.4.1,
  - Mongoose: Version 6.2.5,
  - Nodemon: Version 2.0.15,

## Development Dependencies
  - Artillery: Version 2.0.0-16
