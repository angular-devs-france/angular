# GitHub

## GitHub Repository

- activate Issues on the Settings tab.


## GitHub Issues

- Only keep the bug-report and the feature-request templates. The rest of the templates are not needed for the localization project.
- Update the .github/ISSUE_TTEMPLATE/config.yml` file to remove links.
- Update the `.github/ISSUE_TEMPLATE.md` file to the fork url.


# Deployment

## GitHub Actions

- remove the bazel RBE GitHub Actions from preview build GitHub Action

## Firebase 

- create a project on Firebase Console
- run firebase init hosting to get configuration files and add secrets on the GitHub repository


# Application

## index.html

- update the title and the description of the application
- update the language
- update the different url towards the new one


# Trouble Shooting

## GitHub Actions

- dev-infra/configure.remote does not work from a fork (missing credentials/secrets?)
- removing it has impact upon the CI execution time (16 minutes now vs 4 minutes)

