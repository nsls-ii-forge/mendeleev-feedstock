About mendeleev
===============

Home: https://github.com/lmmentel/mendeleev

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/mendeleev-feedstock/blob/master/LICENSE.txt)

Summary: A perdioc table of elements API and a database of atomic properties.

Development: https://github.com/lmmentel/mendeleev

Documentation: http://mendeleev.readthedocs.org

This package provides an API for accessing various properties
of elements from the periodic table of elements.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=194&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mendeleev-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mendeleev-green.svg)](https://anaconda.org/nsls2forge/mendeleev) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/mendeleev.svg)](https://anaconda.org/nsls2forge/mendeleev) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/mendeleev.svg)](https://anaconda.org/nsls2forge/mendeleev) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/mendeleev.svg)](https://anaconda.org/nsls2forge/mendeleev) |

Installing mendeleev
====================

Installing `mendeleev` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `mendeleev` can be installed with:

```
conda install mendeleev
```

It is possible to list all of the versions of `mendeleev` available on your platform with:

```
conda search mendeleev --channel nsls2forge
```




Updating mendeleev-feedstock
============================

If you would like to improve the mendeleev recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/mendeleev-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


