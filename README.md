# gh-practice
Repository for practicing collaboration on GitHub

This repo is designed to walk new developers through the process of contributing to a shared repository in GitHub.

0. Create a codespace
   - Green "<> Code" button, open a new codespace

1. Create a branch to work on
   - Generally, developers will work on their own branch until ready to share their work with others
   - Create a new branch by running `git checkout -b YOUR_NEW_BRANCH_NAME`
   - Try to choose a branch name that is easy to remember & relates to the changes you plan to make
     - e.g. `adding_widget_v2`, `fixing_duplication_bug`

2. Make your code changes
   - For this example repo, try adding your name to the list of attendees in `practice.py`
   - Once you are happy with your work, commit your changes to the branch:
     - First stage the changes: `git add CHANGED_FILE_NAME`
     - Then commit them: `git commit -m "MESSAGE DESCRIBING THE CHANGE YOU MADE"`

3. Push your changes to GitHub
   - Once you have made all the commit(s) you would like, push the changes to GitHub
   - Run `git push`
   - This will likely give an error because the branch you created does not exist yet on GitHub, only in your Codespace
   - So, you will need to create the branch while pushing by running `git push --set-upstream origin YOUR_NEW_BRANCH_NAME`

4. Open a pull request
   - After pushing, git will suggest opening a pull request (PR) by following a link in your browser
     - e.g.  `https://github.com/awdleishman/gh-practice/pull/new/YOUR_NEW_BRANCH_NAME`
   - Verify that the changes shown in the PR are what you intended to change
   - Open the pull request

5. Wait for an admin/ coworker to review & approve your PR
   - Please be patient!

6. Merge the pull request
   - Generally, best practice is to "Squash & Merge", which combines all commits in a PR into one, keeping the repo history cleaner
