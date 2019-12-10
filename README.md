Add dynamic URL hash for leaflet from [leaflet-fullHash](https://github.com/KoGor/leaflet-fullHash) for hash that has query strings as in [urlHash](https://github.com/jywarren/urlhash).

### Getting started

- Include leaflet-fullUrlHash.js.

- Add the following code after initializing the leaflet map:
```
    // Assuming your map instance is in a variable called map
    var allMapLayers = {'base_layer_name': leaflet_layer_object,
                        'overlay_name': leaflet_layer_object,
                        'another_overlay_name': leaflet_layer_object};
    var hash = new L.FullHash(map, allMapLayers);
```    
To be used with [leafletjs](https://leafletjs.com/) library.


### License

MIT License. See [LICENSE](https://github.com/KoGor/leaflet-fullHash/blob/master/LICENSE) for details.
