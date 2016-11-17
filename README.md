# HP Unified Functional Testing #

## Preface ##

This plugin will parse UFT results files and report them in XL TestView


## CI status ##

[![Build Status][xltv-hpuft-plugin-travis-image] ][xltv-hpuft-plugin-travis-url]
[![Build Status][xltv-hpuft-plugin-codacy-image] ][xltv-hpuft-plugin-codacy-url]
[![Build Status][xltv-hpuft-plugin-code-climate-image] ][xltv-hpuft-plugin-code-climate-url]


[xltv-hpuft-plugin-travis-image]: https://travis-ci.org/xebialabs-community/xltv-hpuft-plugin.svg?branch=master
[xltv-hpuft-plugin-travis-url]: https://travis-ci.org/xebialabs-community/xltv-hpuft-plugin
[xltv-hpuft-plugin-codacy-image]: https://api.codacy.com/project/badge/Grade/4ccbfe085e53497ca0df627521b6855b
[xltv-hpuft-plugin-codacy-url]: https://www.codacy.com/app/rvanstone/xltv-hpuft-plugin
[xltv-hpuft-plugin-code-climate-image]: https://codeclimate.com/github/xebialabs-community/xltv-hpuft-plugin/badges/gpa.svg
[xltv-hpuft-plugin-code-climate-url]: https://codeclimate.com/github/xebialabs-community/xltv-hpuft-plugin


## Usage ##

To use this plugin:

* Using gradle and Docker: `./gradlew runDocker`
* Using an existing XL TestView installation:
  1. Move the [jar file](https://github.com/xebialabs-community/xltv-hpuft-plugin/releases) into the /plugins directory of your XL TestView server installation
  2. Restart XL TestView if it's already running

You will now be able to import HP UFT results. Enter the import directory as the root folder where your UFT files are saved.  For example if you have multiple results such as Res1, Res2, Res3, use the directory where those folders are stored.


