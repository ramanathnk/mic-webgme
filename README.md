# MiniProject1
## Installation
First, install the MiniProject1 following:
- [NodeJS](https://nodejs.org/en/) (v4.x.x recommended)
- [MongoDB](https://www.mongodb.com/)

Second, start mongodb locally by running the `mongod` executable in your mongodb installation (you may need to create a `data` directory or set `--dbpath`).

Then, run `webgme start` from the project root to start . Finally, navigate to `http://localhost:8888` to start using MiniProject1!


The problem I am solving here is making a fault tree representation for a deployment at a web based company.

The deployment go-ahead can be prevented for several reasons. The reasons a deployment can be prevented are shown in the fault tree.

Reason 1 : Test code coverage failed. The unit test must have a minimum coverage.
Reason 2 : Unit tests failed. The unit tests need to pass for a deployment to happen.
Reason 3 : Regression tests failed. The regression tests are tests that make sure that previously created functionality are still working.
Reason 4 : If any one or more of the above tests fail the QA can still give a go ahead. It that fails too then the deployment go-ahead is prevented.

This is demostrated using  a fault tree diagram in web gme.


