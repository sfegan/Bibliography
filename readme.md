## bibliography

This repository houses my BibTeX database which can be included in papers and
notes a a git subtree. To add it to another repository use:

````$
git remote add bibliography https://github.com/sfegan/Bibliography.git
git subtree add --squash --prefix=bibliography bibliography main
````

To pull upstream changes into the repository do:

````$
git subtree pull --squash --prefix=bibliography bibliography main
````

To push additions made to the database back upstream use:

````$
git subtree push --prefix=bibliography bibliography main
````
