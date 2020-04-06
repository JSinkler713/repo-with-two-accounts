## Have a repo on two accounts
### Steps
<ul>
<li>Check the remotes with git remote -v</li>
<li>Make a repo on the non-enterprise account and get url
<li>Add new remote for non-enterprise account
git remote add notEnt https://github.com/JSinkler713/repo-with-two-accounts.git</li>
<li>Push to other repo git push notEnt master</li>
<li>Now we are done</li>
</ul>

#### Code
1. `git remote -v`
2. `git remote add notEnt https://github.com/JSinkler713/repo-with-two-accounts.git`
3. `git push notEnt master`
