# Overview
Fork and clone this repo to have a sample setup every time you want to create a new GitHub repo. This repo uses [repo2docker](https://github.com/jupyter/repo2docker) to simply utilize any packages, data, code, etc. related to this project.  All you have to do for adding new packages is add a package within the `/binder/requirements.txt` file.  

# Using the Repo
Once you have the git repository, add any requirement packages you want your repo to have within the `/binder/requirements.txt` file.  Afterwards, push your changes to GitHub.  Finally, run this command:
`jupyter-repo2docker <source-repository>`
In this case, the source-repository will be the URL of your GitHub repo. Additionally, within the git repo's root directory run the command:
`jupyter-repo2docker --editable .`
This will make it so that any changes within the repo that are made are edited and stored locally.  You can then push these local changes to your remote git repo and have them stored on GitHub.  
