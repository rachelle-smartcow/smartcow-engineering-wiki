# 🔁 Development Lifecycle

### Code Review & Pull Requests

A pull request is the main and only way that code should reach a production environment.

1. Pull code and create a branch&#x20;
   * The first thing that you do is to pull existing code locally. We use the **git** version control system which is deployed on our own servers.&#x20;
2. Create a local branch off 'master', or work on 'dev' branch
3. Work on code
   * This is the fun part! Keep in mind - don't over-engineer the implementation and don't do premature optimizations.
4. Create commits with proper [karma](http://karma-runner.github.io/6.3/dev/git-commit-msg.html)&#x20;
5. Create a pull request on Github&#x20;
   * Once you have pushed your commits to your branch, create a Pull Request, requesting the merge of your local branch into the main source branch. At least one person should be added as a pull request reviewer.
6. Once approved, commit the merge
