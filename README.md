# Current Build Status

Linux, OSX: [![Build Status](https://travis-ci.org/csdms-stack/sedflux-recipe.svg?branch=master)](https://travis-ci.org/csdms-stack/sedflux-recipe)

# About sedflux

Home: http://csdms.colorado.edu/wiki/Model:HydroTrend

Package license: MIT

Summary: Basin filling stratigraphic model

# Installing sedflux

To install sedflux from the csdms channel with `conda`:
```bash
$ conda config --add channels conda-forge
$ conda config --add channels csdms
```

Once these channels have been activated:
```bash
$ conda install sedflux
```

It is possible to list all of the versions of sedflux available on your
platform with:

```
$ conda search sedflux --channel csdms
```
