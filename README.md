# Tab swipe
Swipe to navigate between tabs.

## Dependencies
Mendix 6.5

## Demo project
http://tabswipe.mxapps.io

![1](./assets/demo.gif)

## Usage
- Place the widget in the same page/snippet as the target tab container (right below it).
- Add the name of the target tab container / tab control to the widget (found in the common tab of the tab container properties in the modeler)

## Issues, suggestions and feature requests
We are actively maintaining this widget, please report any issues or suggestions for improvement
https://github.com/mendixlabs/tab-swipe/issues

## Development
Prerequisite: Install git, node package manager, webpack CLI, grunt CLI

To contribute, fork and clone.

    > git clone https://github.com/mendixlabs/tab-swipe.git

The code is in typescript. Use a typescript IDE of your choice, like Visual Studio Code or WebStorm.

To set up the development environment, run:

    > npm install

Create a folder named `dist` in the project root.

Create a Mendix test project in the dist folder and rename its root folder to `dist/MxTestProject`.
Changes to the widget code shall be automatically pushed to this test project.
[https://github.com/mendixlabs/tab-swipe/releases/download/v0.1.0/TestTabSwipe.mpk](https://github.com/mendixlabs/tab-swipe/releases/download/v0.1.0/TestTabSwipe.mpk)

To automatically compile, bundle and push code changes to the running test project, run:

    > grunt
