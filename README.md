About xorg-libxxf86vm
=====================

Home: https://www.x.org/

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/xorg-libxxf86vm-feedstock/blob/main/LICENSE.txt)

Summary: Extension library for the XFree86-VidMode X extension

Development: https://cgit.freedesktop.org/xorg/lib/libXxf86vm

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/xorg-libxxf86vm-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-xorg--libxxf86vm-green.svg)](https://anaconda.org/qtforge/xorg-libxxf86vm) | [![Conda Downloads](https://img.shields.io/conda/dn/qtforge/xorg-libxxf86vm.svg)](https://anaconda.org/qtforge/xorg-libxxf86vm) | [![Conda Version](https://img.shields.io/conda/vn/qtforge/xorg-libxxf86vm.svg)](https://anaconda.org/qtforge/xorg-libxxf86vm) | [![Conda Platforms](https://img.shields.io/conda/pn/qtforge/xorg-libxxf86vm.svg)](https://anaconda.org/qtforge/xorg-libxxf86vm) |

Installing xorg-libxxf86vm
==========================

Installing `xorg-libxxf86vm` from the `qtforge` channel can be achieved by adding `qtforge` to your channels with:

```
conda config --add channels qtforge
conda config --set channel_priority strict
```

Once the `qtforge` channel has been enabled, `xorg-libxxf86vm` can be installed with `conda`:

```
conda install xorg-libxxf86vm
```

or with `mamba`:

```
mamba install xorg-libxxf86vm
```

It is possible to list all of the versions of `xorg-libxxf86vm` available on your platform with `conda`:

```
conda search xorg-libxxf86vm --channel qtforge
```

or with `mamba`:

```
mamba search xorg-libxxf86vm --channel qtforge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search xorg-libxxf86vm --channel qtforge

# List packages depending on `xorg-libxxf86vm`:
mamba repoquery whoneeds xorg-libxxf86vm --channel qtforge

# List dependencies of `xorg-libxxf86vm`:
mamba repoquery depends xorg-libxxf86vm --channel qtforge
```




Updating xorg-libxxf86vm-feedstock
==================================

If you would like to improve the xorg-libxxf86vm recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`qtforge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `qtforge` channel.
Note that all branches in the conda-forge/xorg-libxxf86vm-feedstock are
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

* [@hmaarrfk](https://github.com/hmaarrfk/)

