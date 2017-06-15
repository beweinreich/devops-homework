# Density DevOps Homework Assignment

## Goal
Your goal is to illustrate how you would install and perform regular updates to an application we need to run in our cloud infrastructure.

## Assignment
Your task is to accomplish the following:

- Deploy the sample python application in a manner such that it has immutable deployments and can be scaled horizontally.
- The application should only be available over HTTPS
- Illustrate how you would perform an update to the production application 
- Document how we can launch a specific feature-branch version of the application ready for "QA"
- Please use a container-based deployment approach
- Illustrate how the application would be tested through a CI framework
- Bonus: Briefly document how you would deploy this application in a VM-based deployment fashion


## Don't Let the Dog Eat Your Homework

For delivery of this assignment, we'd like to see:

- A Dockerfile
- Scripts necessary for running through a CI pipeline
- Scripts necessary for continuous delivery to a production environment
- Scripts necessary for setup and teardown of the infrastructure
- Scripts involved with scaling the application horizontally

Create a new repo using your Github account with a unique name and send us the final product!


## Notes

- Please do not fork or submit a PR to this repo
- Please document your thought-processes and use well-written git commit messages to show your progress
- Feel free to change the python application and its requirements in any way you see fit
- We are purposefully not being overly prescriptive in this assignment, as we want you to think creatively about the solution
- This assignment should take less than 3 hours to complete
- If you get stuck or need more information, please reach out for clarity
- Have fun!

## Getting Started in Local Development

Please create and source your virtualenv before beginning. 

```
pip install -r requirements.txt
sqlite3 database.db < schema.sql
python app.py
```