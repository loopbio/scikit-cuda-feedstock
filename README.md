About scikit-cuda
=================

Home: http://github.com/lebedov/scikit-cuda

Package license: BSD License

Feedstock license: BSD 3-Clause

Summary: Python interface to GPU-powered libraries.



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/loopbio/scikit-cuda-feedstock.svg?style=shield)](https://circleci.com/gh/loopbio/scikit-cuda-feedstock)
OSX: [![TravisCI](https://travis-ci.org/loopbio/scikit-cuda-feedstock.svg?branch=master)](https://travis-ci.org/loopbio/scikit-cuda-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/loopbio/scikit-cuda-feedstock?svg=True)](https://ci.appveyor.com/project/loopbio/scikit-cuda-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/loopbio/scikit-cuda/badges/version.svg)](https://anaconda.org/loopbio/scikit-cuda)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/loopbio/scikit-cuda/badges/downloads.svg)](https://anaconda.org/loopbio/scikit-cuda)

Installing scikit-cuda
======================

Installing `scikit-cuda` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `scikit-cuda` can be installed with:

```
conda install scikit-cuda
```

It is possible to list all of the versions of `scikit-cuda` available on your platform with:

```
conda search scikit-cuda --channel loopbio
```




Updating scikit-cuda-feedstock
==============================

If you would like to improve the scikit-cuda recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/scikit-cuda-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
