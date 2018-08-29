git remote add bibliography https://github.com/sfegan/Bibliography.git
git subtree add --prefix=bibliography bibliography master
git subtree push --prefix=bibliography bibliography master
git subtree pull --prefix=bibliography bibliography master
