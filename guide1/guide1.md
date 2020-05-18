# Making a Repository in a Folder That Already Has Files
This is very easy and not hard to do.

If you have code that you want to publish to a remote, but you haven't made a repository in there yet, this guide will tell 
you how to initialise a Git repository in your pre-existent code.

All you need to do is open a Git command line where you want the repository to be, and enter the following:
- `git init`
- `git commit -m "MESSAGE"` — a recommended first commit for your pre-existent code is something like **Initial seed of [code],** so if I were publishing something called "EPG Program," I'd say **Initial seed of EPG Program**

Now there should be a repository in your code which you can set a remote for and push.