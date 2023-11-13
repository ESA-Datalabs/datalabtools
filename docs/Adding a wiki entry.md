# How to add a Wiki entry

## 1. Check out the repository

```bash

git clone https://github.com/ESA-Datalabs/datalabtools.git

```

## 2. Create a new branch

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

## 5. Wait for the pull request to be merged

Once the pull request is merged, your wiki entry will be published on the [Datalabs Wiki](https://github.com/ESA-Datalabs/datalabtools/wiki)