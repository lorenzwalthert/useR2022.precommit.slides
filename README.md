# UseR 2022 talk: Better commits with pre-commit

**Abstract**

Nearly everyone who works with code uses the version control system `git`. However, making good commits (content, scope, message) is something one has to learn. The {precommit} R package provides an interface to the language-agnostic framework `pre-commit`, which allows users to run checks on the code to commit so-called git hooks. These help you to sort out trivial problems like code formatting, as well as linting, ensuring up-to-date derivatives (e.g. `.Rd`, `README.md`) and more. This increases the quality of commits–and ultimately the whole code base.

By attending this talk, you will learn how to set up pre-commit for your projects locally, as well as enforcing the hooks on continuous integration via the recently added support for R in pre-commit.ci. The author will also demo various configuration settings that `pre-commit` supports and show you how to create pre-commit hooks idiosyncratic to your projects.

Source: https://user2022.r-project.org/program/talks/

*** 

Accompanying demo repo: https://github.com/lorenzwalthert/useR2022.precommit.demo
