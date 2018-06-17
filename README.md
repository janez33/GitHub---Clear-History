# GitHub---Clear-History
Clear history from forked GitHub repository
<br>
-- Remove the history from <br>
rm -rf .git

-- recreate the repos from the current content only
git init
git add .
git commit -m "Initial commit"

-- push to the github remote repos ensuring you overwrite history
git remote add origin https://github.com/youraccount/githubrepository.git
git push -u --force origin master
