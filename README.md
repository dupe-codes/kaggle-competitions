This is where I compete in Kaggle competitions :]

## Environment setup

This repo follows a conda + poetry environment setup following the rough mold of this 
[StackOverflow question's top answer](https://stackoverflow.com/questions/70851048/does-it-make-sense-to-use-conda-poetry).

### To create a new conda environment

`conda env create -n {name} -f {environment-osx.yaml | environment-linux.yaml}`
`conda activate {name}`
`poetry install`

### To update an existing environment conda or poetry dependency changes

`conda env update -f {environment-osx.yal | environment-linux.yaml} --prune`
`poetry update`

