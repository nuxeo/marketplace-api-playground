# Nuxeo API Playground

## About

This project allows to build the Marketplace package for the
`nuxeo-api-playground` addon.

The API Playground available offers an interactive way to discover the Nuxeo Platform API.
This module runs fully client side in JavaScript, and makes use of the API of 
Nuxeo Platform it targets.
You can use it on any server as long as you deployed on it a CORS configuration.
      
For further information please read the [documentation](http://doc.nuxeo.com/x/9QUuAQ).

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## Installing

To install the package:

 1. Take a fresh Nuxeo CAP (>= 6.0).

 2. Install the nuxeo-api-playground package:
      - From the AdminCenter (Upload + install)
      - From the command line using `nuxeoctl mp-install package.zip`