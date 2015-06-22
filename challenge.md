![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?

<!-- Answer Starts Here -->
git clone git@github.com:payne-chris-r/git-basics-08-assessment.git
<!-- Answer Ends Here -->

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?

<!-- Answer Starts Here -->
git status (git diff for more detail)
<!-- Answer Ends Here -->

3. Oops - it looks like there was a change that we forgot to include in our last commit. How can we revise that commit and fix things?

<!-- Answer Starts Here -->
If it's just the comment/message use git commit --amend. If you need to go back and redo the whole thing you can use git reset --hard, but that will also erase any changes you've made. I would likely just use git add and make a new commit including the changed files that were missed in the previous commit.
<!-- Answer Ends Here -->

4. It looks like there was a change on the original repo that we forked from. How could we grab those changes and incorporate them into our local repo?

<!-- Answer Starts Here -->
git pull upstream will update your pull request to include any new changes that were made since you forked the original repo.
<!-- Answer Ends Here -->

5. Suppose that we wanted to look at the third-to-last commit on `master`; what command(s) would we write to do that?

<!-- Answer Starts Here -->
git log and look through them starting at the top and scrolling down, or git checkout HEAD~3
<!-- Answer Ends Here -->

6. OK, we've done all the work we want to do locally. Let's update our fork so that we can make a pull request. What command would we use to update our fork?

<!-- Answer Starts Here -->
git push origin
<!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
