# Intercity Bus Simulation using Leaflet.js

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) [![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](http://ansicolortags.readthedocs.io/?badge=latest) [![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com) 
[![GitHub version](https://badge.fury.io/gh/Naereen%2FStrapDown.js.svg)](https://github.com/Naereen/StrapDown.js)
[![GitHub forks](https://img.shields.io/github/forks/Naereen/StrapDown.js.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/Naereen/StrapDown.js/network/)


This project is a web-based intercity bus route simulation built using Leaflet.js and Leaflet Routing Machine. It visualizes buses traveling between major cities (e.g., Jakarta, Bandung, Semarang) in Indonesia on an interactive map. The simulation displays real-time estimated positions, bus details, progress bars, and route directions dynamically.

## Features

Realistic simulation of intercity bus movements with randomized speed and occupancy.
Beautiful UI with popup cards showing:
- Bus operator name
- License plate (randomly generated)
- Route code and route name
- Progress bar with live bus icon
- ETA (Estimated Time of Arrival)
- Passenger occupancy

Custom styled route lines and popups using Google-like colors and modern design.
Route interpolation with animation frame update for smooth movement.
Built entirely in HTML, CSS, and JavaScript with no backend required.

## Tech

Uses a number of open source projects to work properly:
- Leaflet.js – For map rendering.
- Leaflet Routing Machine – For generating routes and step-by-step coordinates.
- Pure HTML, CSS (with Google Fonts), and JavaScript (no frameworks).

## Installation

To run this intercity bus simulation locally, follow these simple steps:

1. Clone or Download the Repository

You can either:

Clone via Git (recommended):
```
git clone https://github.com/ridwan89/BusTracking.git
```
Or download the ZIP archive directly from the GitHub repository and extract it.

2. Open the Application

This project is entirely front-end based and does not require any server or build tools. To launch the simulation: 

- Navigate to the project folder.
- Open the file index.html using any modern web browser (e.g., Chrome, Firefox, Edge).

💡 No need to install Node.js, NPM, or any dependencies. Everything is self-contained and works offline.


## License

[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![PyPI status](https://img.shields.io/pypi/status/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/) [![PyPI format](https://img.shields.io/pypi/format/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
