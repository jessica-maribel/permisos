
# Ionic CLI
The Ionic command-line interface (CLI) is the go-to tool for developing Ionic apps.

## Install

`npm install -g @ionic/cli`

## Architecture
The Ionic CLI is built with TypeScript and Node.js. It supports Node 10.3+

## Project Structure
In a multi-app project, project structure is flexible. The only requirement is a multi-app ionic.config.json file at the root of the repository.

Below is an example setup, where apps in the apps/ directory are separated from the shared code in the lib/ directory. Notice the root ionic.config.json file and the monorepo's package.json file.

## Using ionic init
If an app was created in a way other than `ionic start`, for example by using a prebuilt template, use ionic init to register the existing app with the multi-app project.
