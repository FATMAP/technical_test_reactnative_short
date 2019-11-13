# technical_test_reactnative_short

Simple expo react native app to use as basis to talk about code in interviews

## Installation

```bash

yarn install
yarn start

```

## Some topics to talk about

### Run through / lifecycle

* A bit theoretical:  What's the lifecycle of this react native app?
* How would you test the app?

### TypeScript

* In the current state, the app doesn't really make use of TypeScript, or does it?
* Where, in this app, could we make (better) use of TypeScript right now?

### Tasks

* Fix the app so that the map shows the area where the GeoJSON line is being drawn on startup.
* Extract the GeoJSON line to a seperate file and load it and display it once the map is rendered.
* Extend the app so that it uses tab navigation, with the app being shown in the initial tab and a second tab that shows the raw JSON of the GeoJSON line.
* Using a publically available web endpoint that serves GeoJSON, implement the loading and rendering of GeoJSON loaded over the internet.

Some sources of public GeoJSON serving APIs:

https://earthquake.usgs.gov/fdsnws/event/1/
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2014-01-01&endtime=2014-01-02
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/significant_week.geojson

http://dati.retecivica.bz.it/services/meteo/v1/stations
