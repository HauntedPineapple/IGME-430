## Cloning
If you want to clone a repository including its submodules you can use the --recursive parameter.

`git clone --recursive <URL to Git repo>`

If you already have cloned a repository and now want to load it’s submodules you have to use submodule update.

```
git submodule update --init
# if there are nested submodules:
git submodule update --init --recursive
```

Since a repository can include many submodules, downloading them all sequentially can take much time. For this reason clone and submodule update command support the --jobs parameter to fetch multiple submodules at the same time.

```
# download up to 8 submodules at once
git submodule update --init --recursive --jobs 8
git clone --recursive --jobs 8 <URL to Git repo>
# short version
git submodule update --init --recursive -j 8
```

To pull everything including the submodules, use the --recurse-submodules and the --remote parameter in the git pull command.

```
# pull all changes in the repo including changes in the submodules
git pull --recurse-submodules
# pull all changes for the submodules
git submodule update --remote
```








<hr>

* [Submodules Tutorial](https://www.vogella.com/tutorials/GitSubmodules/article.html)
* [Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)