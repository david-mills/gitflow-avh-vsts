# gitflow-avh-vsts
git flow hooks to enable automatic pull request creation when finishing a release in git-flow.

To enable copy this file into the .git/hooks folder of your repo.  This hook will create a pull request automatically from master to develop - this is in the scenario where the develop branch is protected by branch policies which forbid direct pushes.  The pull request will be set to automatically complete when all branch policies are satisfied.

To enable the hook, the pushproduction git flow flag must be set for the repo (e.g. git config --global gitflow.release.finish.pushproduction true)




