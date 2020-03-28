YOUR OWN EC2 with Jenkins installed.
And have a CI/CD pipeline correctly:
CI:
- listens to dev-branch
- Tests code in slave node (EXTRA: you can do this Monday setting up a slave is hard)
- Merges code and push to master
