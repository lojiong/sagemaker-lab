# sagemaker-lab
# From the Studio Lab terminal, navigate to your home directory.

# Initialize the directory as a Git repository using the following command. 
git init

# Move all of your artifacts, including the Conda environments’ YAML file definitions, to your home directory.
# Add all relevant files and then commit your changes.

$ git add <FILE_NAME>
$ git commit -m "<COMMIT_MESSAGE>"

# Push the commit to your remote repository. 
# This repository has the format https://github.com/<GITHUB_USERNAME>/<REPOSITORY_NAME> where <GITHUB_USERNAME> is your GitHub user name and the <REPOSITORY_NAME> is your remote repository.

$ git remote add origin git@github.com/<GITHUB_USERNAME>/<REPOSITORY_NAME>
$ git push -u origin <BRANCH_NAME>
