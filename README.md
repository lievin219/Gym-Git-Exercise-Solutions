# Gym-Git-Exercise-Solutions

# Bundle 1
# exercise 1











# bundle2 
# exercise2
```bash 
mishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git log --oneline
15e1082 (HEAD -> main, origin/main, origin/HEAD) Merge pull request #1 from lievin219/ft/bundle-2
aa9f2bd changed and added a readme file for  keeping history of the comands i hae been using
ed88bec (origin/ft/bundle-2)  from brancg ft/bundle i created a serives html file
d43cb75 creating a pull reequest
6ed8354 updates on about.html
2d3582a updteson home.html
c4ca1d9 updates about team.html
25c46c9 committed
4b22d2f updated all branch that were added and others that were tested
0360ba6 (origin/dev) first commit
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git branch ft/service-redesign
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git switch ft/service-redesign
Switched to branch 'ft/service-redesign'
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git add .
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git commit -m "made some changes in my service page"
[ft/service-redesign fabd5bf] made some changes in my service page
 Committer: Gym Ishyaka <gymishyaka@Ishyakas-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 4 insertions(+), 1 deletion(-)
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git commit -m "made some changes in my service page"
On branch ft/service-redesign
nothing to commit, working tree clean
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git push -u origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 398 bytes | 398.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/lievin219/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote: 
To https://github.com/lievin219/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git switch main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git add . 
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git commit -m "added some changes in service page on main branch"
[main 99fd04b] added some changes in service page on main branch
 Committer: Gym Ishyaka <gymishyaka@Ishyakas-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 7 insertions(+)
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 393 bytes | 393.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/lievin219/Gym-Git-Exercise-Solutions.git
   15e1082..99fd04b  main -> main
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git switch ft/service-redesign 
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git merge main
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git add .
gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git commit -m "merged and resolved conflicts"
[ft/service-redesign 83e971e] merged and resolved conflicts
 Committer: Gym Ishyaka <gymishyaka@Ishyakas-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

gymishyaka@Ishyakas-iMac Gym-Git-Exercise-Solutions % git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 430 bytes | 430.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/lievin219/Gym-Git-Exercise-Solutions.git
   fabd5bf..83e971e  ft/service-redesign -> ft/service-redesign
   ```
   








