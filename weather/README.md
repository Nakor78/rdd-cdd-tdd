# cli-weather

![logo accueil](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSEUzIraMjD-jpcluTStw4xSqlaLs54xXRzM-x9F34oqgh6tNkG)

### Features

Displays the current conditions and the forecast for the next 4 days of a city.

### Tech

cli-weather uses :

* [node.js] - evented I/O for the backend

### Installation

Different packages need to be downloaded before :

```
$ npm install public-ip
$ npm install chalk
$ npm install cli-table
$ npm install minimist
$ npm install public-ip
$ npm i
```

#### Commands

- The default city is the server's location :
```
$ node index.js
```

##### Options

- ```-a```, ```--address``` pass address
- ```-s```, ```--save``` save preset(s)
- ```--long``` pass longitude (requires --lat)
- ```--lat``` pass latitude (requires --long)
- ```-c```, ```--config``` use metric
- ```-h```, ```--help``` display the help
- ```-v```, ```--verbose``` verbose

### Example

Forecast Weather at Puteaux :

![example1](http://img11.hostingpics.net/pics/414353201602231.png)

License
----

Alexandre Brulé