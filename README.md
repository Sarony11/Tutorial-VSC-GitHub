# Tutorial How to configure Visual Studio Code with GitHub #
With this tutorial we intent to explain and document how to configure Visual Studio Code with GitHub

# Requirements #
- Visual Studio Code -> https://code.visualstudio.com/docs/?dv=win
- GitHub Account -> https://github.com/
- Git -> https://git-scm.com/download/win

# Steps #
## Create a directory on the local file system ##
> mkdir myrepo

## Create a repo on Github ##
> username/myrepo

## Select Clone "Clone or download" on Github, copy the link ##
> https://github.com/username/myrepo.git

## In Visual Studio Code ##
- Select File -> Add Folder to Workspace -> Select the newly created directory ##

## Select Terminal Window ##
- Inicialice: Incialice the local respository
> git init

## Go to Source Control (left menu) ##

- Refresh: Refresh changes
- Commit: Type a message and press CNTL+ENTER (commit)

## In terminal ##
- Main Branch: Create main branch where to push::
> git remote add origin https://github.com/username/myrepo.git

## Go to Source Contrl (lef menu) ##
- Push: Click on the 3 dots and Push
- Autenticate: If you are not already autenticate, do it.

# NOTE: You have to run Visual Code Studio as administrator user. #
