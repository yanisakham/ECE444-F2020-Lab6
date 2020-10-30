# ECE444-F2020-Lab6 

This repo is a clone of the tutorial from https://github.com/mjhea0/flaskr-tdd

## What are the pros and cons of TDD

### Pros:
* This ensures a level of confidence in our functionality. By enforcing tests as part of the employment pipeline, we are less likely to find bugs or issues with the code after it has been deployed to our production environment.
* DTT helps ensure that any modifications to specific modules does not create any new problems that we had not accounted for or thought of when changing the code. This attempts to make sure that while fixing bugs we don't create more bugs
* This practice also encourages developers to be more thoughtful with their design choices and code quality. Tests can help others on your team understand your code, since they also act as examples of how the functions/classes/apis are supposed to work and what the input/output data should look like.

### Cons: 
* TDD takes more time/overhead during the initial stage of the project, which may hinder quick prototyping/development. The time taken to create tests and the deployment pipeline could be instead spent working on actual features and functionality. In addition to maintaining the source code, time must also be taken to maintain the unit testing code as well. This may limit a developer's ability to work on more 'valuable' or results-affecting tasks.
* It also takes time to write unit tests well -- especially with APIs or functionality that highly depends on other modules or clients. This will require dependency injection or client-mocks which are non-trivial and take time to write. 
* If unit tests are written incorrectly, it can be even more consequential than not having them as developers may have to take time to debug their own functional code and the unit tests 
