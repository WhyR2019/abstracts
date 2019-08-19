# Using R6 classes to communicate with a REST API

Author: Patrik Drhlik (Freelance Data Scientist)

# Description

I'll show a project where I developed an R package that uses a main R6 class that connects to a remote production or local development PHP server.

The PHP server offers a REST API for getting data into R that can be then analysed by other functions in the package.

The R6 class manages the following:
- server authentication using a JWT token
- differentiates between a development and a production server
- uses a configuration file to store sensitive credentials that shouldn't be in a repository
- wraps HTTP requests to always send the JWT token in the HTTP Authorization header
- parses all server responses into data frames
- exposes an API to get desired data from the server

It would be possible to talk more than 5 minutes about the project. I don't mind any presentation form. 

