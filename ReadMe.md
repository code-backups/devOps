superlinter.yaml file

name: Super-Linter

Run this workflow every time a new commit is pushed to your repository on: [push, workflow dispatch]
jobs:

Set the job kery. The key is displayed as the job name when a job name is not provided.
super-lint:

Name the job
name: Lint code base

Set the type of machine to run on
runs-on: ubuntu-latest

steps:

Check out a copy of your repository on the ubunti-latest machine
name: Checkout code uses: actions/checkout@v3
Runs the Super-Linter action
