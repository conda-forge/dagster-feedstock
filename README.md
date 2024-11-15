About dagster-feedstock
=======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/dagster-feedstock/blob/main/LICENSE.txt)


About dagster
-------------

Home: https://github.com/dagster-io

Package license: Apache-2.0

Summary: The data orchestration platform built for productivity.

Documentation: https://dagster.readthedocs.io

Dagster is a system for building modern data applications. Combining an elegant programming model and beautiful tools, Dagster allows infrastructure engineers, data engineers, and data scientists to seamlessly collaborate to process and produce the trusted, reliable data needed in today's world.

About dagster-pipes
-------------------

Home: https://github.com/dagster-io/dagster/tree/master/python_modules/dagster-pipes

Package license: Apache-2.0

Summary: Toolkit for Dagster integrations with transform logic outside of Dagster

About dagster
-------------

Home: https://github.com/dagster-io/dagster

Package license: Apache-2.0

Summary: The data orchestration platform built for productivity.

Documentation: https://dagster.readthedocs.io

Dagster lets you define pipelines in terms of the data flow between reusable, logical components,
then test locally and run anywhere. With a unified view of pipelines and the assets they produce,
Dagster can schedule and orchestrate Pandas, Spark, SQL, or anything else that Python can invoke.

Dagster is designed for data platform engineers, data engineers, and full-stack data scientists.
Building a data platform with Dagster makes your stakeholders more independent and your systems
more robust. Developing data pipelines with Dagster makes testing easier and deploying faster.


About dagster-graphql
---------------------

Home: https://github.com/dagster-io/dagster/tree/master/python_modules/dagster-graphql

Package license: Apache-2.0

Summary: The GraphQL frontend to python dagster.

About dagster-webserver
-----------------------

Home: https://github.com/dagster-io/dagster/tree/master/python_modules/dagster-webserver

Package license: Apache-2.0

Summary: Web UI for dagster.

About dagit
-----------

Home: https://github.com/dagster-io/dagster/tree/master/python_modules/dagit

Package license: Apache-2.0

Summary: Dagster UI

About dagster-airflow
---------------------

Home: https://github.com/dagster-io/dagster/tree/master/python_modules/dagster-airflow

Package license: Apache-2.0

Summary: Airflow plugin for Dagster

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=8550&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/dagster-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagit-green.svg)](https://anaconda.org/conda-forge/dagit) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagit.svg)](https://anaconda.org/conda-forge/dagit) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagit.svg)](https://anaconda.org/conda-forge/dagit) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagit.svg)](https://anaconda.org/conda-forge/dagit) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagster-green.svg)](https://anaconda.org/conda-forge/dagster) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagster.svg)](https://anaconda.org/conda-forge/dagster) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagster.svg)](https://anaconda.org/conda-forge/dagster) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagster.svg)](https://anaconda.org/conda-forge/dagster) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagster--airflow-green.svg)](https://anaconda.org/conda-forge/dagster-airflow) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagster-airflow.svg)](https://anaconda.org/conda-forge/dagster-airflow) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagster-airflow.svg)](https://anaconda.org/conda-forge/dagster-airflow) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagster-airflow.svg)](https://anaconda.org/conda-forge/dagster-airflow) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagster--graphql-green.svg)](https://anaconda.org/conda-forge/dagster-graphql) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagster-graphql.svg)](https://anaconda.org/conda-forge/dagster-graphql) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagster-graphql.svg)](https://anaconda.org/conda-forge/dagster-graphql) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagster-graphql.svg)](https://anaconda.org/conda-forge/dagster-graphql) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagster--pipes-green.svg)](https://anaconda.org/conda-forge/dagster-pipes) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagster-pipes.svg)](https://anaconda.org/conda-forge/dagster-pipes) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagster-pipes.svg)](https://anaconda.org/conda-forge/dagster-pipes) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagster-pipes.svg)](https://anaconda.org/conda-forge/dagster-pipes) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dagster--webserver-green.svg)](https://anaconda.org/conda-forge/dagster-webserver) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dagster-webserver.svg)](https://anaconda.org/conda-forge/dagster-webserver) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dagster-webserver.svg)](https://anaconda.org/conda-forge/dagster-webserver) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dagster-webserver.svg)](https://anaconda.org/conda-forge/dagster-webserver) |

Installing dagster
==================

Installing `dagster` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `dagit, dagster, dagster-airflow, dagster-graphql, dagster-pipes, dagster-webserver` can be installed with `conda`:

```
conda install dagit dagster dagster-airflow dagster-graphql dagster-pipes dagster-webserver
```

or with `mamba`:

```
mamba install dagit dagster dagster-airflow dagster-graphql dagster-pipes dagster-webserver
```

It is possible to list all of the versions of `dagit` available on your platform with `conda`:

```
conda search dagit --channel conda-forge
```

or with `mamba`:

```
mamba search dagit --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search dagit --channel conda-forge

# List packages depending on `dagit`:
mamba repoquery whoneeds dagit --channel conda-forge

# List dependencies of `dagit`:
mamba repoquery depends dagit --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating dagster-feedstock
==========================

If you would like to improve the dagster recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/dagster-feedstock are
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

* [@bollwyvl](https://github.com/bollwyvl/)
* [@mgasner](https://github.com/mgasner/)
* [@xhochy](https://github.com/xhochy/)


<!-- dummy commit to enable rerendering -->

