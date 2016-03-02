These are the instructions on how to deploy these docs to https://phase2.github.io/devtools

1) Install mkdocs via `pip install mkdocs`
2) Clone the docs site `git clone git@github.com:phase2/phase2.github.io.git` into ~/Projects
3) Write the docs you want in this directory
4) Build the site. `mkdocs build --clean --site-dir ~/Projects/phase2.github.io/devtools`
5) Add, commit and push the changes in the _devtools_vm repository
6) Add, commit and push the changes in the phase2.github.io repository
