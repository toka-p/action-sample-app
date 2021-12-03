Github Action Notes
===================

## Need to add a self hosted runner
- Following instructions from https://github.com/toka-p/action-sample-app/settings/actions/runners/new
- Apparently it is a software that runs on specific machine that coordinates with github
- went with defaults (just entered through it)
- a new runner "fedora" appeared on gitbub

## Creating workflow
- create a new folder .github/workflows at project root
- add yaml file
- commit and push
- apparently this does run on githbub alone so we may not need a separate runner