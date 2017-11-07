# Beginner guides

These guides are aimed at beginners who want to submit their firt pull requests or that want to start contributing to open source.

This is a step-by-step guide that may help guide you on where to start if you want to contribute to any of our projects listed in <https://github.com/survival>, but should also be helpful if you wanted to contribute to any open source project that lives on GitHub.


## What you will need

* You need to know how to use git, either through a GUI applicaton or through the terminal. CodeSchool has [a good tutorial on git](https://try.github.io/levels/1/challenges/1).

* Since most of our projects are in [GitHub](https://github.com), you will need to have an account there. Jessica Lord has [the best tutorial on Github](https://github.com/jlord/git-it-electron).

* It helps to know how to use the terminal as well, since most of our projects need you to run commads, for example, to run the tests. Codebar has a starter tutorial on [the command line](http://tutorials.codebar.io/command-line/introduction/tutorial.html).


## Where to start

* Search for issues in any of our repos with the label `good-first-issue`.

* When you find a project you want to contribute to, fork the repository by clicking the "Fork" button on the top right of the project's home page.

![alt text][forkit]

* This will create a copy of our project in your GitHub account. This allows you to modify the project safely in your account and once you're happy with the changes you can submit it to us (see **Starting your contribution** below).

* Now that you have a copy of our project in your GitHub account, you can clone it to your computer. If you are using the terminal, type `git clone PROJECT_URL_HERE`. You can find the project's URL to clone in your copy of the project, clicking the big green "clone or donwload" button to the right:

![alt text][clone-url]

* The final step is to add our project's url as a remote so that you can fetch changes from it often and keep your copy updated. The URL can be found in the same place where you found your copy's URL. If you are using the terminal, type `git remote add upstream PROJECT_URL_HERE`.


## Set up

* If the project is a Ruby project, check that your local Ruby version is the same as in the Gemfile, if not, change it locally. You may need to [install it if you don't have it](https://cbednarski.com/articles/installing-ruby/). How to do this depends on the ruby version manager that you use. Search for its documentation.

* Install `bundler` if you haven't installed it for that version of Ruby (`gem install bundler`)

* Follow the instructions in the README to set the project up, run the tests and the app, and check that everything works before starting your work. If you have any problems contact us: [webmaster@survivalinternational.org](mailto:webmaster@survivalinternational.org)


## Starting your contribution

* Create a branch from master. If you are on the terminal, type `git checkout -b branch-name-here`.

* Write your code and tests, and make sure that the tests pass before submitting your work.

* When you are finished, push your branch to GitHub. If you are on the terminal, type `git push origin branchname`.

* If you go to your copy's page on GitHub now, you will see a banner informing you that you pushed a branch. You can submit a pull request directly from there, by clicking on the big green "Compare & pull request" button.

![alt text][clone-url]

* Fill in the textbox with a description of what you have done and click "Create pull request". When you do this we will receive your changes and review them! Hopefully your pull request will be merged into our project, but if not, we will indicate the things you can improve.


## Keeping your copy up to date

Any time you want to keep your copy up to date with any new changes we have made in our project, you can checkout the master branch (if you are using the terminal, type `git checkout master`) and then pull any new changes (if you are using the terminal, type `git pull upstream master`).


[forkit.png]: https://github.com/survival/contributing-guides/images/forkit.png "How to fork the project"
[clone-url.png]: https://github.com/survival/contributing-guides/images/clone-url.png "How to clone the project"
[pull-request.png]: https://github.com/survival/contributing-guides/images/pull-request.png "How to make a pull request"
