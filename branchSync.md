# Utility workflow to keep all branches in sync

To distribute a change on master I use the following script

```bash
opencode$ pwd
/Users/opencode/git/github/open-prevo

opencode$ rm -rf slides && git clone git@github.com:open-prevo/slides.git && cd slides

# https://stackoverflow.com/questions/67699/how-to-clone-all-remote-branches-in-git
opencode$ git checkout master ; remote=origin ; for brname in `git branch -r | grep $remote | grep -v HEAD | awk '{gsub(/^[^\/]+\//,"",$1); print $1}'`; do git branch -D $brname ; git checkout -b $brname $remote/$brname ; done ; git checkout master

# https://stackoverflow.com/questions/5292184/merging-multiple-branches-with-git
opencode$ for BRANCH in $(git branch); do git checkout $BRANCH ; git merge --no-edit origin/master $BRANCH ; git status ; done

opencode$ git push --all
```
