# github-action-version-bump
Testing out actions version bump in npm packages

- to bump `minor`: use `feat` or `feature` in commit message
- to bump `major`: use `BREAKING CHANGE` or `major` in commit message
- to bump patch: don't use any of the above keywords in commit message.

#### How to use
1. **clone repo using ssh** (just in case)
2. Make a change to main.js
3. commit change.
4. push change to master. 
5. viola, view version number change automagically. :dancer:
