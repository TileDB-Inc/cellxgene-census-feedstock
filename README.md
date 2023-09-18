About cellxgene-census-feedstock
================================

Feedstock license: [BSD-3-Clause](https://github.com/TileDB-Inc/cellxgene-census-feedstock/blob/main/LICENSE.txt)



Package license: MIT

Summary: API to facilitate the use of the CZ CELLxGENE Discover Census. For more information about the API and the project visit https://github.com/chanzuckerberg/cellxgene-census/

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/TileDB-Inc/CI/_build/latest?definitionId=44&branchName=main">
        <img src="https://dev.azure.com/TileDB-Inc/CI/_apis/build/status/cellxgene-census-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cellxgene--census-green.svg)](https://anaconda.org/tiledb/cellxgene-census) | [![Conda Downloads](https://img.shields.io/conda/dn/tiledb/cellxgene-census.svg)](https://anaconda.org/tiledb/cellxgene-census) | [![Conda Version](https://img.shields.io/conda/vn/tiledb/cellxgene-census.svg)](https://anaconda.org/tiledb/cellxgene-census) | [![Conda Platforms](https://img.shields.io/conda/pn/tiledb/cellxgene-census.svg)](https://anaconda.org/tiledb/cellxgene-census) |

Installing cellxgene-census
===========================

Installing `cellxgene-census` from the `tiledb` channel can be achieved by adding `tiledb` to your channels with:

```
conda config --add channels tiledb
conda config --set channel_priority strict
```

Once the `tiledb` channel has been enabled, `cellxgene-census` can be installed with `conda`:

```
conda install cellxgene-census
```

or with `mamba`:

```
mamba install cellxgene-census
```

It is possible to list all of the versions of `cellxgene-census` available on your platform with `conda`:

```
conda search cellxgene-census --channel tiledb
```

or with `mamba`:

```
mamba search cellxgene-census --channel tiledb
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search cellxgene-census --channel tiledb

# List packages depending on `cellxgene-census`:
mamba repoquery whoneeds cellxgene-census --channel tiledb

# List dependencies of `cellxgene-census`:
mamba repoquery depends cellxgene-census --channel tiledb
```




Updating cellxgene-census-feedstock
===================================

If you would like to improve the cellxgene-census recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tiledb` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tiledb` channel.
Note that all branches in the TileDB-Inc/cellxgene-census-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Shelnutt2](https://github.com/Shelnutt2/)

