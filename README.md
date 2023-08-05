### dbquakes
Quakes database USGS extract, for use in planetA visualizer

#### dbquakes4planet.py is the database-creation component of project planetA

dbquakes4planet.py creates a date-delimited request, parses the JSON response
from earthquake.usgs.gov JSON, and stores a subset in a table in the quakes.db 
sqlite database (by convention, the table name is qq + startdate and enddate.)
