# te-lodging
New Year's Resolutions - Travel 

* https://mapzen-data.github.io/targeted-editing/te-lodging/map
* https://mapzen.com/blog/new-years-resolutions-travel
* https://mapzen.com/blog/targeted-editing-retrospective/

## Parts

* Map - [map/index.html](map/index.html)
* Scene file (powers the map) - [map/hotel.yaml](map/hotel.yaml)
* Map interactivity - [map/main.js](map/main.js)
* Queries
	* [queries/lodging_sql.sql](https://github.com/mapzen-data/targeted-editing/blob/gh-pages/queries/lodging_sql.sql) original queries
	* [queries/new_lodging_sql.sql](https://github.com/mapzen-data/targeted-editing/blob/gh-pages/queries/new_lodging_sql.sql)  reporting change since original blog post

### To run locally:

Download this repo, then start a web server in its directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to: [http://localhost:8000](http://localhost:8000)
