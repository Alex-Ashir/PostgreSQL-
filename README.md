# PostgreSQL is a type of a database management system that is called a free and open-source relational databse management system (RDBMS).




i) PostgreSQL database will be used along with its PostgreSQL client libraries.
ii) Applications will be ArcGIS Server, ArcGIS Pro, ArcGIS Desktop, and ArcReader.



Note:
Your ability/knowledge to execute PostgreSQL commands will open new opportunities and expand beyond general thinking.
Example 1:
What is the total length of all roads in California state?
SELECT sum(ST_Length(the_geom))/1000 AS km_roads FROM ca_roads;

km_roads
000000000000

Example 2:
How large is the city of San Francisco, California?

SELECT ST_Area(the_geom)/10000 AS hectares
FROM ca_municipality
WHERE name = 'SAN FRANCISCO';

hectares
000000000000
 
