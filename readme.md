# consistent git aliases

This plugin takes the hard work and thinking from [@davidde/git](https://github.com/davidde/git) 
to provide a framework-agnostic set of consistent git aliases.

[@jedahan](https://github.com/jedahan) basically just removed the custom functions and OMZ specific stuff.

To use this, just source it somewhere in your zshrc

# Aliases

| Alias           | Command                                                   |
|:----------------|:----------------------------------------------------------|
| **g**           | git                                                       |
| **ga**          | git add                                                   |
| **gaa**         | git add --all                                             |
| **gam**         | **g**it commit --**a**mend -**m**                         |
| **gama**        | **g**it commit --**a**mend -**m** --**a**ll               |
| **gan**         | **g**it commit --**a**mend --**n**o-edit                  |
| **gana**        | **g**it commit --**a**mend --**n**o-edit --**a**ll        |
| **gb**          | git branch                                                |
| **gba**         | git branch --all                                          |
| **gbd**         | git branch --delete                                       |
| **gbdf**        | git branch --delete --force                               |
| **gbl**         | git blame                                                 |
| **gbls**        | git branch --list \| cat                                  |
| **gbs**         | git bisect                                                |
| **gbsb**        | git bisect bad                                            |
| **gbsg**        | git bisect good                                           |
| **gbsr**        | git bisect reset                                          |
| **gbss**        | git bisect start                                          |
| **gc**          | git commit --verbose                                      |
| **gcam**        | git commit -am                                            |
| **gcamg**       | git commit -am --gpg-sign                                 |
| **gcams**       | git commit -am --signoff                                  |
| **gcf**         | git config                                                |
| **gcfl**        | git config --list                                         |
| **gcfls**       | git config --list \| cat                                  |
| **gcl**         | git clone --recurse-submodules                            |
| **gcm**         | git commit -m                                             |
| **gcmg**        | git commit -m --gpg-sign                                  |
| **gcms**        | git commit -m --signoff                                   |
| **gco**         | git checkout                                              |
| **gcob**        | git checkout -b                                           |
| **gcod**        | git checkout develop                                      |
| **gcom**        | git checkout master                                       |
| **gcp**         | git cherry-pick                                           |
| **gcpa**        | git cherry-pick --abort                                   |
| **gcpc**        | git cherry-pick --continue                                |
| **gd**          | git diff                                                  |
| **gds**         | git diff --staged                                         |
| **gdst**        | git diff stash@{0}                                        |
| **gdsth**       | git diff stash@{0} HEAD                                   |
| **gdstp**       | git diff stash@{0}^ stash@{0}                             |
| **gf**          | git fetch                                                 |
| **gfo**         | git fetch origin                                          |
| **ggb**         | git graph branches                                        |
| **gl**          | git log --name-status                                     |
| **glg**         | git log --graph                                           |
| **glgo**        | git log --graph --oneline                                 |
| **glgs**        | git log --graph --stat                                    |
| **glo**         | git log --oneline                                         |
| **glog**        | git log                                                   |
| **glr**         | git log --reverse --name-status                           |
| **gls**         | git ls-files                                              |
| **gm**          | git merge                                                 |
| **gmom**        | git merge origin/master                                   |
| **gmum**        | git merge upstream/master                                 |
| **gmv**         | git mv                                                    |
| **gp**          | git push                                                  |
| **gpd**         | git push --delete                                         |
| **gpdo**        | git push --delete origin                                  |
| **gpf**         | git push --force-with-lease                               |
| **gpt**         | git push && git push --tags                               |
| **gpl**         | git pull                                                  |
| **gplr**        | git pull --rebase                                         |
| **gplrs**       | git pull --recurse-submodules                             |
| **gr**          | git reset                                                 |
| **grhard**      | git reset --hard                                          |
| **grhardh**     | git reset --hard HEAD                                     |
| **grk**         | git reset --keep                                          |
| **grkh**        | git reset --keep HEAD                                     |
| **grs**         | git reset --soft                                          |
| **grsh**        | git reset --soft HEAD                                     |
| **grb**         | git rebase                                                |
| **grbm**        | git rebase master                                         |
| **grem**        | git remote                                                |
| **grema**       | git remote add                                            |
| **gremset**     | git remote set-url                                        |
| **gremsh**      | git remote show                                           |
| **gremv**       | git remote -v                                             |
| **grl**         | git reflog                                                |
| **grm**         | git rm                                                    |
| **gs**          | git status                                                |
| **gsh**         | git show                                                  |
| **gst**         | git stash                                                 |
| **gsta**        | git stash apply                                           |
| **gstd**        | git stash drop                                            |
| **gstl**        | git stash list                                            |
| **gstls**       | git stash list \| cat                                     |
| **gstp**        | git stash pop                                             |
| **gstsl**       | git stash show -l                                         |
| **gstsp**       | git stash show -p                                         |
| **gsubi**       | git submodule update --init                               |
| **gsubu**       | git submodule update --remote --merge                     |
| **gt**          | git tag                                                   |
| **gtam**        | git tag -am                                               |
| **gtsm**        | git tag -sm                                               |
| **gtd**         | git tag --delete                                          |
| **gtl**         | git tag --list                                            |
| **gtls**        | git tag --list \| cat                                     |
| **gwch**        | git whatchanged -p                                        |
