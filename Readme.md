
# NASA BlueMarble Shaded Relief Bathymetry Tiles - Labeled

![npm](https://img.shields.io/npm/v/@freetiler/nasa-bluemarble-labeled)

This NPM package provides access to tiles from the NASA BlueMarble_ShadedRelief_Bathymetry set, which are believed to be in the public domain. These tiles feature detailed representations of Earth's surface combining shaded relief and bathymetry (underwater topography). Labels originate from Open Street Map data.

## Usage

The tiles can be used offline, hosted on your own servers, or accessed via the included CDN link for easy integration into web mapping applications.

To install the tiles offline via NPM, use:
```
npm install @freetiler/nasa-bluemarble-labeled
```

### CDN Links

You can use any NPM or Github CDN to serve the tiles. 

```
GitHub CDN - Zoom 0-8: 
 - https://cdn.jsdelivr.net/gh/freetiler/nasa-bluemarble-labeled/tiles/{z}/{x}/{y}.jpeg

NPM CDNs - Zoom 0-7:
 - https://esm.sh/@freetiler/nasa-bluemarble-labeled/tiles/{z}/{x}/{y}.jpeg
 - https://unpkg.com/@freetiler/nasa-bluemarble-labeled/tiles/{z}/{x}/{y}.jpeg
```

## Tile Specs:

- **Minimum Zoom Level**: 0
- **Maximum Zoom Level on NPM**: 7
- **Maximum Zoom Level on Github**: 8
- **Projection Used**: EPSG:3857
- **Tile Size**: 256x256
- **Tile Format**: JPEG
- **Attribution**: "FreeTiler.com | NASA | OSM Contributors"

## License

This package distributes NASA tiles. Please do your own due diligence to confirm this before use.

Open StreetMaps License:
This dataset is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/


## Disclaimer

This package is provided "as is", without warranty of any kind. Use at your own risk.
