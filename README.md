# teja.dev


### to run local server
`hugo server --disableFastRender -D`

### to push code
`git submodule sync`
`git submodule foreach 'echo $sm_path `git rev-parse HEAD`'`

### to build pages
`hugo -D`
