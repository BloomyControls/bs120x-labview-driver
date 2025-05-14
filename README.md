# Battery Simulator 1200 & 1201 LabVIEW Driver

This package provides an API for controlling the Bloomy BS1200 and BS1201 cell simulators in LabVIEW.  The API exposes nearly all of the capabilities of the cell simulators including execution control via ethernet or CAN, and configuration via Ethernet.  The library is cross compatible in that it can interact with both legacy BS1200 and the latest BS1201 units using the same functions on the same ethernet port or CAN bus.

## Installation

The BS120x LabVIEW API is distributed as a VI Package which can be downloaded from this repository's [releases page](https://github.com/BloomyControls/bs120x-labview-driver/releases). After downloading the VI package, double click to install using VI Package Manager.

The package can also be rebuilt from source using the VI package build specification at `./build/bs120x.vipb`.

## Examples

The BS120x LabVIEW API package will install an example FIs under `<LabVIEW Examples\Bloomy\Battery Simulator 120x`. These examples demonstrate:
+ Discovery
+ Configuration
+ Execution

## Development

The BS120x LabVIEW API is developed using the following software
+ [LabVIEW 2021 SP1 64-bit](https://www.ni.com/en/support/downloads/software-products/download.labview.html#443865)

## License

Copyright (c) 2025, Bloomy Controls, Inc. All rights reserved.

This software is distributed under the BSD-3-clause license. See the LICENSE
file or <https://opensource.org/license/BSD-3-Clause> for details.
