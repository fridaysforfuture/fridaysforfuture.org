# FridaysForFuture.org
This repository is used to develop and maintain the international website of FridaysForFuture, a grassroots movement urging politicians and media to treat the climate crisis as a serious threat.

## Prerequisites
The project uses the css preprocessor Less, utilizing Node.js to install and run the npm modules less and less-watch-compiler.

[Install Node.js](https://nodejs.org/en/)

Once node.js has been installed, open your command window (cmd/bash) to install less and less-watch-compiler.

Less
```bash
npm install -g less
```
less-watch-compiler
```bash
npm install -g less-watch-compiler
```

Open a command window in the directory of the repository and use the following command to start the automatic compilation process
```bash
less-watch-compiler
```

## Contribute
Fork and clone the repository

Branch explanations:
- The master branch is meant to represent the current stable version which is live.
- The hotfix branch is meant for quick bug fixes on the stable version.
- The develop branch is where any new development occurs.

To contribute, select an issue from our issue board to work on. For all issues which are not urgent bugs, create a new branch based on develop and work on the issue there. Commit every so often and once you are done with the issue and you feel your code is ready to go live, create a pull request with your code. This code will then be reviewed by one or several repository admins.

## Community
We communicate on a discord server. Contact linahanner to receive an invitation (we are working on a better solution to send invitations)