# GitHub Runners

## To have the submodules (i.e., the auditor) update automatically with pulls
```shell
git config --global submodule.recurse true
```
The above might not work if you made local changes to the submodule, so the fool-proof command is to call to get the most recent updates as needed
```
git submodule update --init --recursive
```

## To do:
- [x] Run example runner
- [x] Run example runner and create a file
- [x] Run an example file and add it to the commit
- [x] Run the example and try doing that in Python
- [x] Make the python auditor into a submodule (automate submodule updates)
- [ ] See if you can generate an html page using a python virtual environment and plotly
- [ ] See if you can push the updates to a website remotely that has a github pages

## References:
- [GitHub submodules](https://github.blog/2016-02-01-working-with-submodules/)
- [Notes](https://www.overleaf.com/read/nqwzsywgcdgn)
