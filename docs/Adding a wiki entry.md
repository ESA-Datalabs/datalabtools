# How to add a Wiki entry
Depending on if you are already a collaborator in this repository or not, this changes slightly.

## 1. Check out the repository

### 1.1. For collaborators

In this case you are already added to the repsoitory as a collaborator, and you can proceed with the git clone command

```bash

git clone https://github.com/ESA-Datalabs/datalabtools.git

```

### 1.2. For the public

In this case you do not have write and push permissions to the repo. Therfore, please Fork the repo from the repo's homepage and clone from your forked repo.


```bash

git clone https://github.com/{YOURUSERNAME}/datalabtools.git

```

## 2. Create a new branch

Navigate to the cloned folder and create a new branch.

```bash

git checkout -b my-new-wiki-entry

```

## 3. Create a new file

Create a new markdown file in the `docs` folder with the title of the wiki entry. For example, if the title of the wiki entry is "Adding a wiki entry", the file name should be `Adding a wiki entry.md`.

Write your article.

## 4. Commit your file to the repo and create a pull request

```bash

git add docs/Adding\ a\ wiki\ entry.md
git commit -m "Add wiki entry: Adding a wiki entry"
git push origin my-new-wiki-entry

```

Then go to [the GitHub repo and open a pull request](https://github.com/ESA-Datalabs/datalabtools/compare).
If you have previously forked the repo, open a pull request and click on 'compare across forks' and select your fork in the 'head repository' dropdown menu.

## 5. Wait for the pull request to be merged

Once the pull request is merged, your wiki entry will be published on the [Datalabs Wiki](https://github.com/ESA-Datalabs/datalabtools/wiki)