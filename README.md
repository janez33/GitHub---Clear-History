# GitHub---Clear-History
Clear history from forked GitHub repository
<br>
<i>-- Remove the history from</i><br>
rm -rf .git

<i>-- recreate the repos from the current content only</i><br>
git init<br>
git add .<br>
git commit -m "Initial commit"<br>

<i>-- push to the github remote repos ensuring you overwrite history</i><br>
git remote add origin https://github.com/youraccount/githubrepository.git<br>
git push -u --force origin master
