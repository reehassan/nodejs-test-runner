Node.js Test Runner
A simple Node.js project demonstrating a GitHub Actions CI workflow that runs tests on push and pull requests.
Setup

Clone the repository.
Run npm install to install dependencies.
Run npm test to execute the test suite.

GitHub Actions Workflow
The workflow (.github/workflows/node-test.yml) triggers on:

Push to the main branch
Pull requests targeting the main branch

It performs the following steps:

Checks out the code using actions/checkout@v4
Sets up Node.js using actions/setup-node@v4
Installs dependencies with npm installs
Runs tests with npm test

Testing
The project uses Jest for testing. Tests are defined in index.test.js.
Files

index.js: Contains a simple sum function.
index.test.js: Tests the sum function.
package.json: Project metadata and scripts.

