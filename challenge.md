![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?

git clone (repo SSH url)

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?

git log

3. Oops - it looks like there was a change that we forgot to include in our last commit. How can we revise that commit and fix things?

git commit --ammend

4. It looks like there was a change on the original repo that we forked from. How could we grab those changes and incorporate them into our local repo?

To get the changes we need to use the command git pull upstream.

5. Suppose that we wanted to look at the third-to-last commit on `master`; what command(s) would we write to do that?

git checkout --HEAD~3

6. OK, we've done all the work we want to do locally. Let's update our fork so that we can make a pull request. What command would we use to update our fork?

git push origin master
<hr>

You're done! Refer back to README.md.
