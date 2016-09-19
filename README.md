# Test git 
#this is Test reposotry for practice Git

git config 

git add

git add '*.txt' (or) git add --All
git add doc/
// doc is directory name

git commite -m 'Added with comment'

git remote add origin https://github.com/try-git/try_git.git

git push -u origin master

// rement to add -u this will remembere for next time.

git pull origin master

git diff HEAD

git add octofamily/octodog.txt
// to add staged file 

git diff --staged

git reset octofamily/octodog.txt

git checkout -- octocat.txt
//git reset did a great job of unstaging octodog.txt, but you'll notice that he's still there. He's just not staged anymore. It would be great if we could go back to how things were before octodog came around and ruined the party.

git branch clean_up
//clean_up is baranch name to create brance for developers


git checkout clean_up

git rm '*.txt'
//  rm is for remove files from stage 

git commit -m "Remove all the cats"

git checkout master

git merge clean_up

git branch -d clean_up
// -d will delete the branch for 
