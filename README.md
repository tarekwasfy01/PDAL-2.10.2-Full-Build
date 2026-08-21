# PDAL 2.10.2 Full Build

Full build of **PDAL 2.10.2** for Windows.

PDAL (Point Data Abstraction Library) is an open-source library and command-line toolkit for processing, converting, filtering and analyzing point cloud data.

## Included

* PDAL 2.10.2
* Full command-line tools
* LAS / LAZ point cloud support
* Point cloud conversion
* Filtering and processing pipelines
* Coordinate system transformations
* Raster and point cloud interoperability
* PDAL pipeline support
* Additional drivers and dependencies included in the build

## Check Version

```powershell
pdal --version
```

## Example

```powershell
pdal info input.laz
```

Convert a file:

```powershell
pdal translate input.laz output.las
```

Run a pipeline:

```powershell
pdal pipeline pipeline.json
```

## License

PDAL is open-source software distributed under the **BSD License**.

Official project:

https://github.com/PDAL/PDAL

Documentation:

https://pdal.io/

## Version

**PDAL 2.10.2 Full Build**
