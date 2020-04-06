## Have a repo on two accounts
### Steps
1. Check the remotes
  a. Make a repo on the non-enterprise account and get url
2. Add new remote for non-enterprise account
3. Push to other repo git push notEnt master</li>
4. Check that it pushed to the new non-ent repo

#### Code
1. `git remote -v`
2. `git remote add notEnt https://github.com/JSinkler713/repo-with-two-accounts.git`
3. `git push notEnt master`
