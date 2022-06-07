# README file for the HelloWorld interview assignment
Assignment for Chris Page.  Pipeline file can be found at .circleci/config.yml

## How you would modify your pipe to accommodate for dev and prod environments
I currently have the pipeline looking at the branch name.  If the name isn't "prod" it will use the cicd credentials.  If it is "prod" then it will use a 'custom' set of credentials for deployment.  I don't have two environments to deploy to, so I have the same credentials set in both places.

## What challenges you had, what you didn’t have time for, and what you would change
My biggest challenge was getting connected to AWS.  I was able to clone the repo and get started in CircleCI pretty easily.  CircleCI is fairly similar to how Azure Devops does their configuration files, and from what I've played with so far I think I prefer how CircleCI does things over ADO.  Another challenge was that I didn't have quick access to a linux environment to test locally (I haven't set up my linux partition since my last hard drive wipe).  

I didn't have time to complete the assignment from start to finish in 3 hours.  If it was a system I was already set up in though, 3 hours would have been more than sufficient.

I'm not sure how/if I'd change anything about this assignment.  I find that there will usually be first time setup technical difficulties when using a new set of tools or environment.  With a little more time than the 3ish hours I was able to complete the assignment and implement the dev vs prod options.
