**Problem**

When I try to push my app to Heroku I get this response:

_fatal: 'heroku' does not appear to be a git repository_
_fatal: Could not read from remote repository._

Please make sure you have the correct access rights
and the repository exists.
I have tried 'heroku keys:add' but still comes up with the same result. I already have an ssh key for my GitHub account.

**Solution**

First, make sure you're logged into heroku:

_heroku login_

Enter your credentials.

It's common to get this error when using a cloned git repo onto a new machine. Even if your heroku credentials are already on the machine, there is no link between the cloned repo and heroku locally yet. To do this, cd into the root dir of the cloned repo and run

_heroku git:remote -a yourapp_
