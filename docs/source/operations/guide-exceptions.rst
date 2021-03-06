Armada Exceptions
=================

+------------------------+----------------------------------------------------------+
| Exception              | Error Description                                        |
+========================+==========================================================+
| KnownReleasesException | Occurs when no known releases are found.                 |
+------------------------+----------------------------------------------------------+

Tiller Exceptions
=================

+------------------------------------+--------------------------------------------------------------------------------------------+
| Exception                          | Error Description                                                                          |
+====================================+============================================================================================+
| ChartCleanupException              | An error occurred removing a chart.                                                        |
+------------------------------------+--------------------------------------------------------------------------------------------+
| ListChartsException                | An error occurred listing helm charts.                                                     |
+------------------------------------+--------------------------------------------------------------------------------------------+
| PostUpdateJobDeleteException       | An error occurred deleting a job after an update.                                          |
+------------------------------------+--------------------------------------------------------------------------------------------+
| PostUpdateJobCreateException       | An error occurred creating a job after an update.                                          |
+------------------------------------+--------------------------------------------------------------------------------------------+
| PreUpdateJobDeleteException        | An error occurred deleting a job before an update.                                         |
+------------------------------------+--------------------------------------------------------------------------------------------+
| PreUpdateJobCreateException        | An error occurred creating a job before an update.                                         |
+------------------------------------+--------------------------------------------------------------------------------------------+
| ReleaseUninstallException          | A release failed to uninstall.                                                             |
+------------------------------------+--------------------------------------------------------------------------------------------+
| ReleaseInstallException            | A release failed to install.                                                               |
+------------------------------------+--------------------------------------------------------------------------------------------+
| ReleaseUpdateException             | A release failed to update.                                                                |
+------------------------------------+--------------------------------------------------------------------------------------------+
| TillerPodNotFoundException         | Tiller pod could not be found using the labels specified in the Armada config.             |
+------------------------------------+--------------------------------------------------------------------------------------------+
| TillerPodNotRunningException       | Tiller pod was found but is not in a running state.                                        |
+------------------------------------+--------------------------------------------------------------------------------------------+
| TillerServicesUnavailableException | Occurs when Tiller services are unavailable.                                               |
+------------------------------------+--------------------------------------------------------------------------------------------+

Chartbuilder Exceptions
=======================

+-----------------------------+-------------------------------------------------------------+
| Exception                   | Error Description                                           |
+=============================+=============================================================+
| DepedencyException          | A dependency failed to install.                             |
+-----------------------------+-------------------------------------------------------------+
| HelmChartBuildException     | An error occurred  building the chart.                      |
+-----------------------------+-------------------------------------------------------------+
| IgnoredFilesLoadException   | An error occurred loading the ignored files.                |
+-----------------------------+-------------------------------------------------------------+
| MetadataLoadException       | An error occurred loading the metadata for a chart.         |
+-----------------------------+-------------------------------------------------------------+
| UnknownChartSourceException | The chart source is unknown or invalid.                     |
+-----------------------------+-------------------------------------------------------------+

Source Exceptions
=================

+--------------------------+---------------------------------------------------------------------+
| Exception                | Error Description                                                   |
+==========================+=====================================================================+
| GitLocationException     | Repository location is not valid.                                   |
+--------------------------+---------------------------------------------------------------------+
| SourceCleanupException   | The source dir of a chart no longer exists.                         |
+--------------------------+---------------------------------------------------------------------+
| TarballDownloadException | Occurs when the tarball cannot be downloaded from the provided URL. |
+--------------------------+---------------------------------------------------------------------+
| TarballExtractException  | Occurs when extracting a tarball fails.                             |
+--------------------------+---------------------------------------------------------------------+
| InvalidPathException     | Occurs when a non-existent path is accessed.                        |
+--------------------------+---------------------------------------------------------------------+
| ChartSourceException     | Occurs when an unknown chart source type is encountered.            |
+--------------------------+---------------------------------------------------------------------+

Lint Exceptions
===============
+----------------------------------+------------------------------+
| Exception                        | Error Description            |
+==================================+==============================+
| InvalidManifestException         | Armada manifest invalid.     |
+----------------------------------+------------------------------+
| InvalidChartNameException        | Chart name invalid.          |
+----------------------------------+------------------------------+
| InvalidChartDefinitionException  |  Chart definition invalid.   |
+----------------------------------+------------------------------+
| InvalidReleaseException          | Release invalid.             |
+----------------------------------+------------------------------+
| InvalidArmadaObjectException     |  Armada object not declared. |
+----------------------------------+------------------------------+

Manifest Exceptions
===================
+----------------------------------+------------------------------------------------+
| Exception                        | Error Description                              |
+==================================+================================================+
| ManifestException                | An exception occurred while attempting to build|
|                                  | an Armada manifest. The exception will return  |
|                                  | with details as to why.                        |
+----------------------------------+------------------------------------------------+
