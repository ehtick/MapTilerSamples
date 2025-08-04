# MapTiler samples

Code examples of how to use the [MapTiler Maps API](https://www.maptiler.com/cloud/) with live demos.

## Live demos

### MapTiler Cloud

- [Choropleth map basic - docs](https://docs.maptiler.com/sdk-js/examples/countries-filter/)
- [Choropleth geojson - Leaflet](https://labs.maptiler.com/samples/cloud/choropleth-geojson-leaflet/) - [docs](https://docs.maptiler.com/guides/maps-apis/maps-platform/zoomable-choropleth-map-from-geojson-with-leaflet/)
- [Choropleth geojson - MapLibre](https://labs.maptiler.com/samples/cloud/choropleth-geojson-maplibre/) - [docs](https://docs.maptiler.com/guides/maps-apis/maps-platform/zoomable-choropleth-map-from-geojson-with-maplibre/)
- [Choropleth geojson - OpenLayers](https://labs.maptiler.com/samples/cloud/choropleth-geojson-openlayers/) - [docs](https://docs.maptiler.com/guides/maps-apis/maps-platform/zoomable-choropleth-map-from-geojson-with-openlayers/)
- [Countries with own data](https://labs.maptiler.com/samples/cloud/countries-with-own-data/) - [docs](https://docs.maptiler.com/guides/maps-apis/maps-platform/join-maptiler-countries-with-your-own-custom-data-and-make-a-choropleth-map/)

### Cesium

- [Custom lidar](https://labs.maptiler.com/samples/cesium/custom-lidar/) - [docs](https://docs.maptiler.com/guides/map-tiling-hosting/data-hosting/custom-lidar-data-and-cesium/)

## Contributing

Please create a folder per article or usecase in the product's folder. The website has an autobuild to https://labs.maptiler.com/samples/

> When autobuild finished, samples can be found on `https://labs.maptiler.com/samples/[sample path]/`, for example the sample in the `cloud/choropleth-map-basic` folder will end up in [`https://labs.maptiler.com/samples/cloud/choropleth-map-basic/`](https://labs.maptiler.com/samples/cloud/choropleth-map-basic/)

### Where to store data for samples

All data and maps need to be stored in one account in MapTiler Cloud. The account is called [**MapTiler Web**](https://cloud.maptiler.com/account/switch?account_id=a8ee7342-ffd3-45a7-b7c3-1b50050b033d). Ask your teamleader or PO for an access. Please, mark all production datasets with label **PRODUCTION** and please write description to dataset/map with link where it is used for later.

### Where to get key for samples

Please use now just one key: `kIa92mbw58jO4stVhZOO`. We will replace it globally later. The key is under **MapTiler Web** account, so it has access to all uploaded sample data.
