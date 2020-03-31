# Mexitecture


mexitecture is my effort to compile the most interesting milestones in the architecture of Mexico City. Please use the map below to explore the buildings, where they are located and a bit of history who have constructed them. While working on it, I have tried polymer and web-components.

The project is hosted at https://mexitecture.com

### Run project

To run the project locally

```
polymer serve
```

to build the project

```
polymer lint
polymer build

```

the app is deployed with netlify


### Notest on construction

* the main application is located in my-app.html
* used mapbox for mapping, tried google maps but was not customizable

```
bower install —save PolymerVis/mapbox-gl
```

```
 <mapbox-gl-marker
            id="casa-baragan"
            latitude=19.4105
            longitude=-99.1917
            width=64
            height=64
            border-radius="100%"
            background-image="https://placekitten.com/g/64/64"
            >
          </mapbox-gl-marker>
```

* TO-DO struggling to resize pop-up window, can't find how to adjust the class for the mapbox components
* tried css-grid for landing. a little messed up for the small mobile devices
* 