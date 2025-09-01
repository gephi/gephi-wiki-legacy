Recommendations and requirements for how to best contribute to Gephi. We strive to obey these as best as possible, though we may drift as development continues in our primary development branches. As always, thanks for contributing--we hope these guidelines make it easier and shed some light on our approach and processes.

You can build Gephi using ant but the best is to use [NetBeans](http://netbeans.org/) to code in Gephi, as it is based on [Netbeans Platform](http://platform.netbeans.org).

`master` is the ongoing branch for the next major release (e.g., 0.8-beta, 0.9)

### Checkout the code

* Install Git.
* Fork the repository.
* Checkout the repository with your Github account. If asked for a RSA fingerprint, answer yes.

        $ git clone git@github.com:username/gephi.git
* If you get a Permission denied (publickey), something is wrong with your [SSH key](http://help.github.com/win-set-up-git/#_set_up_ssh_keys).

### Set up your repository

* Set up Git's credentials

        $ git config --global user.name "Firstname Lastname"
        $ git config --global user.email "your_email@youremail.com"
* When a repo is cloned, it has a default remote called origin that points to your fork on GitHub, not the original repo it was forked from. To keep track of the original repo, you need to add another remote named upstream:

        $ cd gephi
        $ git remote add upstream git://github.com/gephi/gephi.git
        $ git fetch upstream master
* This is simply keeping your fork up to date. Each time you run git fetch upstream master it downloads the latest change done on the main repository (not your fork). Note that this is NOT changing any of your files. You'll need a merge to actually apply the latest changes to your fork.

#### Push commits

* When you work on the code, commit often! The commit process is straightforward. First add all the files you want to include in your commit:

        $ git add .
* Then commit these files

        $ git commit -m "This is my first commit hourray"
* Run git status often to see what your repository is up to. Your commits are local. To send them to GitHub run:

        $ git push origin master 

### Merge from the main repository

* When we update the main gephi repository, your fork doesn't get updated automatically. To merge the latest commits to your fork, run a merge from upstream:

        $ git fetch upstream master
        $ git merge upstream/master
* To fetch and merge in one line, simply run

        $ git pull upstream master
* When you merge, you may run into conflicts. This is normal if you worked on the same files.
* Note that `git fetch upstream` or `git pull upstream` will download all branches data, which is something you probably don't need. That's why we add `master` to specify which branch to fetch to.

#### Send pull requests

That's the standard and easiest way to contribute to the project. It's fully integrated into GitHub and well explained here.

### How to contribute to the main project

* When you are a member of the gephi team, you have the write rights on the main repository. Instead of submitting pull requests you simply commit to the repository, including the master branch. Change your upstream push url to authenticated version:

        $ git remote set-url upstream git@github.com:gephi/gephi.git
* Push to the master branch. Make sure you pulled to the latest revision before (git pull upstream master).

        $ git push upstream master

### Coding standards

Follow these [guidelines](http://wiki.gephi.org/index.php/Code_Sharing_Strategy).

### Tips

* [Configuring NetBeans](http://wiki.gephi.org/index.php/Configuring_NetBeans)
* [NetBeans Tips](http://wiki.gephi.org/index.php/NetBeans_Tips)
* [Troubleshooting](http://wiki.gephi.org/index.php/Troubleshooting)
