# README file for the HelloWorld interview assignment
Assignment for Chris Page.  Pipeline file can be found at .circleci/config.yml

## How you would modify your pipe to accommodate for dev and prod environments
There are a few ways to go about it, and I'd like to investigate CircleCI a bit more to figure out exactly how I'd do the dev/prod split.  For a prod deployment, I'd want to include a check (email approval or something along those lines) to prevent accidental deployments.  The different deployment locations/credentials could be handled with a switch looking at the branch name.  If it's "dev" use this set of environment variables, if it's "prod" use this other set of environment variables.

## What challenges you had, what you didn’t have time for, and what you would change
My biggest challenge so far has been getting connected to AWS.  I was able to clone the repo and get started in CircleCI pretty easily.  CircleCI is fairly similar to how Azure Devops does their configuration files, and from what I've played with so far I think I prefer how CircleCI does things over ADO.  Another challenge is that I didn't have quick access to a linux environment to test locally (I haven't set up my linux partition since my last hard drive wipe).  

I didn't have time to implement the dev vs prod feature, but I think I have a pretty good idea on how it would do it.  I also didn't have time in the 3ish hours to get the pipeline pushing the built container to AWS.  I was having permission issues but I'm guessing at least part of that is due to the fact that I'm not as familiar with AWS.

I'm not sure how/if I'd change anything about this assignment.  I find that there will usually be first time setup technical difficulties when using a new set of tools or environment.  Given more than 3ish hours I probably would have figured my permissions issues out, and I might keep working on this to figure out what went wrong.  I'm also curious in learning what all CircleCI can do.  
