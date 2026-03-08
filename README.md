# THE FOG IS COMING

FogOfMap is a simple map application using jetpack(tryina teach myself) with a fog of war effect using openstreetmap.
the fog itself will clear around the users current location and their traveled path(and will stay clear) (untill they delete their data or smth)

# TL;DR
the whole gist is to gamify the exploration of the real world


# Features
*(that i hope ill add)*
* the map exploration ofc
* tracing the users latest traveled path - collecting statistics along the way like distance traveled, time it took and the % of the city explored
* bookmarking the spots for later visiting
* history of the older excursions
* ability to export/import traveled paths

***
## technical things
* **kotlin** - main language for the logic
* **Jetpack** - *the star of the show* - for UI and Material 3 implementation
* **MapLibre Compose** - to render OpenStreetMap data in Jetpack
* **gplay services location** - kinda need that for location
* **rooms (maybe with ksp?)** - for exploration sessions and other persistent data
* **kotin coroutines** - kinda important since app needs to update the location and handle other logic aswell
* **material 3** - its a design system idk

***
## **TODOS**
* Task_1: get the map setup!
* Task_2: get users location and track it(with its data)
* Task_3: build a db design to store users latest sessions
* Task_4: make it exportable
