# 01_phaser-game-1
first attempt at phaser by following tuts here

project conception at 1st May 2020

Link to reference on github action nodejs build and test:
https://help.github.com/en/actions/language-and-framework-guides/using-nodejs-with-github-actions#building-and-testing-your-code

Create docker container action:
https://help.github.com/en/actions/building-actions/creating-a-docker-container-action#creating-an-action-metadata-file

build simple game tut:
https://www.freecodecamp.org/news/how-to-build-a-simple-game-in-the-browser-with-phaser-3-and-typescript-bdc94719135/

# Workflow

## First phase:
- repo followed: https://github.com/mariyadavydova/starfall-phaser3-typescript
- accompanied steps: https://www.freecodecamp.org/news/how-to-build-a-simple-game-in-the-browser-with-phaser-3-and-typescript-bdc94719135/

## Adjustment:
- assets/ - new assets
- gameScene.ts - modify according to assets

## Build
- configure necessary packages:
    `npm install -D typescript webpack webpack-cli ts-loader phaser live-server`
- run webpack:
    `npm run-script build`
- start the server:
    `npm start`
