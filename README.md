# dev-box
a vagrant base box based on ubuntu server 16.10 with sensible defaults for development

## installation
this box is available on [atlas](https://atlas.hashicorp.com/boxes/search).
follow these steps:

```bash
# download the box
$ vagrant box add thekelvinliu/dev-box
# navigate to some project
$ cd path/to/project
# initialize the box
$ vagrant init thekelvinliu/dev-box
# start it up
$ vagrant up --provider virtualbox
# connect
$ vagrant ssh
```

## about
- up-to-date ubuntu server 16.10 yakkety yak
- jump-start
  - an offshoot of [osx-jump-start](https://github.com/thekelvinliu/osx-jump-start) with the osx stuff hacked away
  - run `~/jump-start/scripts/linker.sh`
- [python3](https://github.com/python/cpython)
  - [pip3](https://github.com/pypa/pip)
  - [numpy](https://github.com/numpy/numpy)
  - [scipy](https://github.com/scipy/scipy)
  - [matplotlib](https://github.com/matplotlib/matplotlib)
  - [ipython](https://github.com/ipython/ipython)
- [nodejs](https://github.com/nodejs/node)
  - via [nvm](https://github.com/creationix/nvm)
  - [gulp-cli](https://github.com/gulpjs/gulp-cli)
  - [ncu](https://github.com/tjunnone/npm-check-updates)
  - [yarn](https://github.com/yarnpkg/yarn)

## changelog
- 1.0.0
  - 2017-02-23
  - initial release
