![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?

<!-- After you have forked the repo, you have to copy the SSH clone URL. Then, in the command line, you must go to the directory where you would like this new repo. There, you will make sure you're not in another git repo. Once you're safely not in another git repository, you would type 'git clone + the SSH clone URL' to give yourself a local repo to work on. -->

<!-- Answer Ends Here -->

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?

<!-- You could use the command 'git status' to see changes that have been made since the last commit. This would show both staged and unstaged changes.  -->

<!-- Answer Ends Here -->

3. Oops - it looks like there was a change that we forgot to include in our last commit. How can we revise that commit and fix things?

<!-- To revise your previous commit, you would use the command 'git commit --amend'. This command would allow you to replace the message of your previous commit with a revised message. If you need to get rid of a prior commit altogether, you would use the command 'git reset --hard commit-name' but this would destroy commits made since this point. -->

<!-- Answer Ends Here -->

4. It looks like there was a change on the original repo that we forked from. How could we grab those changes and incorporate them into our local repo?

<!-- In order to incorporate changes from the original repo into your local repo, you must pull from upstream (the original repo) and merge with your cloned local repo. Then later, you would push your changes to your origin and eventually submit a pull request from the original you forked from. -->

<!-- Answer Ends Here -->

5. Suppose that we wanted to look at the third-to-last commit on `master`; what command(s) would we write to do that?

<!-- To look at the third-to-last commit on 'master', you would use the command 'git checkout master' to make sure you are starting from your last commit. Then you would use 'git checkout HEAD~2' to bring you back two commits, which would leave you at the third-to-last commit. -->

<!-- Answer Ends Here -->

6. OK, we've done all the work we want to do locally. Let's update our fork so that we can make a pull request. What command would we use to update our fork?

<!-- To update our fork, we would first make sure all changes have been committed. Then we would use the command 'git push origin master' to push our changes to our remote repo. -->

<!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
