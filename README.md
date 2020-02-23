# Overview
This repo will serve as the sample setup every time you want to create a new GitHub repo. This repo uses [repo2docker](https://github.com/jupyter/repo2docker) to simply utilize any packages, data, code, etc. related to this project.  All you have to do for adding new packages is add a package within the `/binder/requirements.txt` file.  

# Create a New Repo
Navigate to [Import a Repo](https://github.com/new/import) on GitHub to create a new repository.  Use this repository as the imported repo, https://github.com/zcox10/template_ds_setup. You'll be able to give the repo a unique name and clone to your local machine.  

# Using the Repo
Once you have cloned the git repository to your local machine, add any requirement packages you want your repo to have within the `/binder/requirements.txt` file.  

Afterwards, push your changes to GitHub.  Finally, run this command:

`jupyter-repo2docker <source-repository>`

In this case, the source-repository will be the URL of your GitHub repo. We'll close out of this environment in order to make it editable with `CTRL + C`.  We'll then run this command within the git repo's root directory in order to save all the local changes we'll make:

`jupyter-repo2docker --editable .`

This will make it so that any changes within the repo that are made are edited and stored locally.  You can then push these local changes to your remote git repo and have them stored on GitHub.  
