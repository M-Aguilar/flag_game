Here are a couple javascript games. The code is in mostly funtional condition. The next step from here is to standardize inputs
with the goal of allowing a limitess iterations of games through providing game elements.
(e.g. flag&countries.csv, countries&names.geojson) 

Flag Game
This script sxpects certain HTML tags with the class "start" and removes them when initiating the game.
Takes a csv file as input with each line containing two comma separated varuables. The first variable being
the question (Flag) and the second being the answer (Country Name).

Country Quiz
This script expects elements with the class "start" when initializing the setup and removes them.
A GeoJSON file is expected with a FeatureCollection of Feature:Countries. 
The GeoJSON that was used in this game was.
