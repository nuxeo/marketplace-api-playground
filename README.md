# Nuxeo API Playground

## About

This project allows to build the Marketplace package for the `nuxeo-api-playground` addon.

The API Playground available offers an interactive way to discover the Nuxeo Platform API.
This module runs fully client side in JavaScript, and makes use of the API of Nuxeo Platform it targets.
You can use it on any server as long as you deployed on it a CORS configuration.

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## QA

[![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=addons_FT_nuxeo-api-playground-master)](https://qa.nuxeo.org/jenkins/job/addons_FT_nuxeo-api-playground-master/)

## Deploying

Install [the nuxeo-api-playground Package](https://connect.nuxeo.com/nuxeo/site/marketplace/package/nuxeo-api-playground).

# Resources

## Documentation

[NXDOC/REST API](http://doc.nuxeo.com/x/9QUuAQ)

## Reporting issues

https://jira.nuxeo.com/browse/NXP/component/13317

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).