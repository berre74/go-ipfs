# berre74/go-ipfs

## Synchronize this forked repository with https://github.com/ipfs/go-ipfs.git


git remote -v
git remote add upstream https://github.com/ipfs/go-ipfs.git
git remote -v

git remote fetch upstream

git checkout master

git merge upstream/master

git remote fetch origin

git push



