[![Moleculer logo](http://moleculer.services/images/banner.png)](https://github.com/ice-services/moleculer)

# Command line tool for Moleculer framework [![NPM version](https://img.shields.io/npm/v/moleculer-cli.svg)](https://www.npmjs.com/package/moleculer-cli)


## Install

``` bash
npm install -g moleculer-cli
```

## Usage

### Init a new project
With this commant you can scaffold a new Moleculer project.

``` bash
moleculer init module my-module
```
The above command download the template from [ice-services/moleculer-template-module](https://github.com/ice-services/moleculer-template-module), prompts some information and generate a new module to the `./my-module` folder.

#### Official templates

* [`module`](https://github.com/ice-services/moleculer-template-module) - Generate a new Moleculer module project (e.g.: `moleculer-xyz`). *Use it if you want to create a module for Moleculer framework*
* [`project-simple`](https://github.com/ice-services/moleculer-template-project-simple) - Generate a simple Moleculer-based project. *Use it if you want to start a new project which is based on Moleculer framework*

#### Custom templates

``` bash
moleculer init username/repo my-project
```
Where username/repo is the GitHub repo shorthand for your fork.

The shorthand repo notation is passed to [download-git-repo](https://github.com/flipxfx/download-git-repo) so you can also use things like bitbucket:username/repo for a Bitbucket repo and username/repo#branch for tags or branches.

#### Local Templates

Instead of a GitHub repo, you can also use a template on your local file system:
``` bash
moleculer init ./path/to-custom-template my-project
```

## Credits
The `moleculer-cli` project `init` command is based on [vue-cli](https://github.com/vuejs/vue-cli) project. 

## Contribution
Please send pull requests improving the usage and fixing bugs, improving documentation and providing better examples, or providing some testing, because these things are important.

## License
Moleculer-cli is available under the [MIT license](https://tldrlegal.com/license/mit-license).

## Contact
Copyright (c) 2017 Ice-Services

[![@ice-services](https://img.shields.io/badge/github-ice--services-green.svg)](https://github.com/ice-services) [![@MoleculerJS](https://img.shields.io/badge/twitter-MoleculerJS-blue.svg)](https://twitter.com/MoleculerJS)
