# Contributing Guide
We welcome your contributions! Please see the provided steps below and never hesitate to contact us.

If you are a new user, we recommend checking out the detailed [Github Guides](https://guides.github.com).

## Setting up a development installation
In order to make changes to `goworking`, you will need to [fork](https://guides.github.com/activities/forking/#fork) the
[repository](https://github.com/fabricadofuturo-poa/goworking).

If you are not familiar with `git`, we recommend reading up on [this guide](https://guides.github.com/introduction/git-handbook/#basic-git).

Clone the forked repository to your local machine and change directories:
```sh
$ git clone https://github.com/your-username/goworking.git
$ cd goworking
```
Set the `upstream` remote to the base `goworking` repository:
```sh
$ git remote add upstream https://github.com/fabricadofuturo-poa/goworking.git
```

Install the required dependencies:
```sh
$ pip install -r requirements.txt
```

### Help us make sure it's you

Each commit you make must have a [GitHub-registered email](https://github.com/settings/emails)
as the `author`. You can read more [here](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address).

To set it, use `git config --global user.email your-address@example.com`.

## Keeping your branches up-to-date

Switch to the `master` branch:
```sh
$ git checkout master
```

Fetch changes and update `master`:
```sh
$ git pull upstream master --tags
```

This is shorthand for:
```sh
$ git fetch upstream master --tags
$ git merge upstream/master
```

Update your other branches:
```sh
$ git checkout your-branch-name
$ git merge master
```

## Sharing your changes

Update your remote branch:
```sh
$ git push -u origin your-branch-name
```

You can then make a [pull-request](https://guides.github.com/activities/forking/#making-a-pull-request) to `goworking`'s `master` branch.


## Code of conduct

`goworking` has a [Code of Conduct](CODE_OF_CONDUCT.md) that should be honored by everyone who participates in the `goworking` community.

## Questions, comments, and feedback

If you have questions, comments, suggestions for improvement, or any other inquiries
regarding the project, feel free to open an [issue](https://github.com/fabricadofuturo-poa/goworking/issues).
