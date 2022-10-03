## PipeLine Process

-   When developers just make a change and send it to the repository, automated package installation, linting, testing, building, and deployment take place.

## Continuous Integration
***
-   One of our pipelines process steps is continuous integration. Its function is to install dependencies, then start linting and constructing the app after you have verified your code and pushed it to the repository. Each commit will carry out this process..

## Continuous Deployment
***
-   Continuous deployment is a pipeline process phase that we use. It truly happens following a continuous integration process that comes after we verify, test, and build our code. It automates the entire procedure and deploys your application without requiring human approval.

## CircleCI
***
-   OneEvery time a developer commits code, CircleCI automatically executes the build and test processes and then updates the GitHub branch with the build progress. The first step is to generate a config.yml file, which CircleCI will read each time it performs a build.

---

### Here is the architecture of the pipeline process...

![PipeLine Process](https://github.com/AlyZakaria/Host-FullStackApp-CircleCI/blob/main/Screenshots/pipelineProcess.png)



