# buffer-lambda-curator
an AWS lambda curator of interesting content for music and technology that posts on my buffer

## What You Will Find Here
This repository contains the swagger description of the API. This API creates all the serverless backend to curate music and articles in my buffer.
It stores nothing at the moment, even though it could be expanded to store and analyse with some machine algorithms the content to improve the accuracy.

This repository is pushed directly onto production and works with codedeploy, sooooo make sure your PULL requests won't break my amazing curator!

There is also all the code for the various lambdas that are linked with the API Gateway.

There is also a lambda that periodically checks for new content and if it finds anything it calls the APIs.

### Regarding the Credentials
All the credentials are stored as environmental variables.

## More Ideas

* create an ansible script for all the environment alongside troposphere 
