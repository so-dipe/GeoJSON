# Nigeria GeoJSON
This Repo contains the map of all states in Nigeria in GeoJSON format.

The files here can be used to plot choropleth maps of data corresponding to different states in the country.

How to use:

Consider, the `Nigeria and its states.geojson` file
Under `features` and under `properties` there are two properties you can use to 
select the states. You can use either the `id` property of the `state` property.

`id` : This is just a number (string like '1' or '20') that can be used to identify all the states in alphabetical order
        (i.e Abia = '1', Zamfara = '37')
        
`state`: This is just the state name in all caps (ex: 'LAGOS', 'FCT')
