# Tutorial How to configure Visual Studio Code with GitHub #
With this tutorial we intent to explain and document how to configure Visual Studio Code with GitHub

# Requirements #
Visual Studio Code -> https://code.visualstudio.com/docs/?dv=win
GitHub Account -> https://github.com/
Git -> https://git-scm.com/download/win

# Steps #
--> Create a directory on the local file system.
    mkdir myrepo

--> Create a repo on Github.
    username/myrepo

--> Select Clone "Clone or download" on Github, copy the link
    https://github.com/username/myrepo.git

--> In Visual Studio Code, sect File -> Add Folder to Workspace -> Select the newly created directory
--> Select Terminal Window and Type:
    git config --global user.name <github userID>
    git clone <URL from github link copied earlier>
    git init

--> Go to Source Control (left menu)
--> Refresh changes
--> Type a message and press CNTL+ENTER (commit)
--> Click on the 3 dots and Push
--> Autenticate


That should be all that's required.  any newly created file should be available on github after stage/commit/push.
