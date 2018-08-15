Grainstore
===========

This is a specific fork of grainstore 1.6.4 for use with [Windwalker](https://github.com/BHare1985/Windwalker). Grainstore 1.6.4 is the latest grainstore that still supports node 4.x.

Specifically, this grainstore fork allows 

- db_type to be supplied such that other providers beside postgis can be used. 
- [layer properties](https://github.com/mapnik/mapnik/wiki/XMLConfigReference#layer) to be passed in (such as the useful `cache-features`)
- uses a specialized [millstone](https://github.com/BHare1985/millstone) that adds support for windows paths as well as supporting linux paths
