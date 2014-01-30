
census-maps notes:

ideally be able to serve this as a SPA up on iainkirkpatrick.me - for it to work properly with github pages though, the data will need to be sitting there in a file (i.e i downloaded and formatted it at some point). hopefully this is possible, it would be the easiest way to get away with not needing a backend database.

- kind of necessitates not much interactivity to the maps - i.e. swapping layers in and out. this is a restriction, but also an opportunity to be clever with design
- i.e. potentially detect where the user is located, and zoom the map extents to their location (given that is where they are most likely to be interested in). 

i like the notion of a SPA, long-scrolling - think some of the Mapbox demo pages, just keep scrolling for different maps with different data? fade-ins, fadeouts? how will long-scrolling work with large map divs, accidental zooming?