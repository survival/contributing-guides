# How to contribute

Regarding our codebases, we have been making efforts to keep the code readable so that if you want to contribute, just by reading the code everything should make sense to you immediately.

However, we thought it would probably be helpful to write down some of the team's tribal knowledge (every team has some).

**We welcome "first pull requests" from beginners as well as from more experienced developers who want to volunteer on our projects**. We will add some issues from time to time to our repos and mark them with the labels `good-first-issue` or `volunteers`.


## Coding standards

The easiest way to get it right is to read the code that already exists and do things as you see they are done. Basically keep the code clean, readable, maintainable and easy to change in the future. Follow good practices, SOLID principles and design patterns. Do the simplest thing that could possibly work. Less code is often better than more code!

We think that "*Readability is more important than cleverness.*". Whatever helps maintainability in the long term is very important to us.


## Tests

Tests not only help make sure that new changes don't break the existing code. More importantly; they help you have a well designed and structured codebase.

Make sure the code you submit with your pull request is covered by tests, and that all the tests pass. We have Travis in place so we won't merge a pull request until Travis is green. We also use Coveralls to make sure we have a healthy test coverage.


## Linters

We use linters to automate syntax checks in all of our projects. It keeps the code consistent when several developers work on the same project. And it avoids wasting time and effort in pull requests correcting syntax. We think this is the kind of task that a robot is happy to do! So the linters run automatically after the tests.

For Ruby projects we use Rubocop, following [the official Ruby style guide](https://github.com/bbatsov/ruby-style-guide). For Javascript, we use ESLint. For Python, we use Flake8.


## Git etiquette

We are fans of a clean git history. You can take a look at  [our git etiquette guide](https://github.com/octopusinvitro/zagakus/blob/master/git-etiquette.md).
Some other pull-request related points from there:

* Small pull requests are easier to review, and are more likely to be merged fast.

* Sometimes we do "cleaning" pull requests before the real pull request, to fix the code first for the change we want to do. "[*Make the change easy, then make the easy change*](https://twitter.com/kentbeck/status/250733358307500032?lang=en)".

* [Commits should have a single responsibility. The description should use verbs in imperative tense and explain the "why"](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

* When you finish your pull request, remember to check if the README needs updating after your change.


## Questions

Please write to us at
[open-source@survivalinternational.org](mailto:open-source@survivalinternational.org).
