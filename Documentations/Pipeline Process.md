# Pipeline Process

We are connecting CircleCi with our Github repo in order to achive the Continious Integration / Continious Development (CI/CD).
The future commits pushed to our project will automatically update our hosted layers of our project 

## Order of commands

1. The pipeline uses orbs to install Node, the AWS cli and the EB cli.
2. It checks out the code from the repo
3. FrontEnd install dependencies
4. FrontEnd build
4. FrontEnd run tests
6. FrontEnd deploy
7. Backend install dependencies
8. Backend build
9. Backend run tests
10. Backend deploy


