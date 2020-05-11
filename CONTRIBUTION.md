# Guidelines

## Git Setup
We follow a systematic Git Workflow -
- Create a fork of this repo.
- Clone your fork of your repo on your pc.
- [Add Upstream to your clone](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)
- **Every change** that you do, it has to be on a branch. Commits on master would directly be closed.
- Make sure that before you create a new branch for new changes,[syncing with upstream](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork) is neccesary.


## Setup and running of project 
* Install [NodeJS](https://nodejs.org/en/) 12.16
* This will also install node package manager [npm](https://www.npmjs.com) in you system 
* Also install [yarn](https://yarnpkg.com) 
* Install Expo CLI on your system. 
    ```
    npm install -g expo-cli
    ```

* Once expo is installed run 
    ```
    yarn run 
    ```
* Choose start and it would generate QR Code
* Install Expo Mobile APP From your App Store and scan the generated QR and magic pixie will render mobile app in your device
* Also if you don't have a device try compiling for expo web using
    ```
    expo start --web
    ```

