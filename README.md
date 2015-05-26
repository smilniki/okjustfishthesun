zpaths
=========
Software Development Spring Term Final Project  
Visit our website:  [http://zpaths.openpaths.cc/](http://zpaths.openpaths.cc/)  
Watch our demo video:  

## About

ZPaths is here to help you with your everyday New Yorker needs. Upon entering our site, you are given 10+ options to choose from for points of interest in the city: from subway entrances, to museums and galleries. We then return a heat map that displays the best areas in New York City to find those points of interest, as well as a bar graph displaying how common these ameneties are in each borough.  

## How to Run Locally

1. open up a terminal and type `$git clone git@github.com:crabalockerfishwife/okjustfishthesun`
2. create a virtual environment (optional) and type `$pip install flask Flask`
3. type `$python app.py` to run the app
4. go to [localhost:8000](localhost:5000) in your browser (Chrome is recommended)

## Tools Utilized

- [Python](https://www.python.org/) and [Flask](http://flask.pocoo.org/) for basic app backbone  
- [Digital Ocean](https://www.digitalocean.com/) for droplet deployment  
- [Gunicorn](http://gunicorn.org/) as a WSGI server  
- [nginx](http://nginx.org/) as a reverse proxy to the Gunicorn server  
- [FreeDNS](http://freedns.afraid.org/) for web hosting  
- [Google Maps API](https://developers.google.com/maps/) for directions and geolocation  
- [Pure CSS](http://purecss.io/) for CSS styling  
- [JQuery](http://jquery.com/) for interactive form widgets  
- [Google Places](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete) for location autocompletion  
- [lodash](https://lodash.com/) for map, filter, reduce functions  
- [NYC Open Data](https://nycopendata.socrata.com/) for JSON data visualization  

## Contributors
[Christina Ko](https://github.com/ChristinaKo): Backend - Google Heatmap Layers API  
[Fish Milnikiewicz](https://github.com/crabalockerfishwife): Styling - CSS, D3, etc.  
[Sunnam Quispe](https://github.com/konceq): Backend - Google Maps API  
[Justin Strauss](https://github.com/justinstrauss): NYC Open Data API, Website Framework

## Timeline
- [X] 4/27: finalize project idea (all)
- [X] 4/29: gather links for JSON data from NYC Open Data
- [X] 5/1: parse out coordinates and addresses
- [X] 5/3: set up single page web app
- [X] 5/5: add floating menu bar
- [X] 5/7: use divs to split the page into sections
- [X] 5/9: generate heatmap for one dataset
- [X] 5/11: make Digital Ocean droplet
- [X] 5/13: use SVG to make cool logo
- [X] 5/15: launch basic website
- [ ] 5/17: test, code review, add any additional features
- [ ] 5/19: use D3 to make bar graphs by borough
- [ ] 5/21: shoot promo video
- [ ] 5/23: edit promo video and post to YouTube
- [ ] 5/25: fin
