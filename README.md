# Aws Full-Stack Cloud Development

# Setup Overview

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code
- AWS CLI
- AWS CDK (cdk CLI)

Later on in the course we will install other software, e.g. PostgreSQL client tools and Redgate Flyway for database versioning ... but for now this is all you need to get started with the first few sections.

## Mac Setup

Firstly go to

```
brew.sh
```

and follow the instructions for installing homebrew. Then use homebrew commands as follows:

```
  brew install --cask google-chrome
  brew install node
  brew install git
  brew install --cask git-credential-manager
  brew install --cask visual-studio-code
  brew install awscli
  brew install aws-cdk
  git-credential-manager configure
```

## Windows setup

Open a new powershell terminal in admin mode and run the following commands.

The first command ensures that the other programs work without security issues once they are installed - you may well get errors without it!

```
  Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  winget install Google.Chrome
  winget install OpenJS.NodeJS
  winget install Git.Git
  winget install GitHub.GitCredentialManager
  winget install Microsoft.VisualStudioCode
  winget install Amazon.AWSCLI

```

then in a new terminal (to ensure node and npm are on the path)

```
  npm install -g aws-cli
```
