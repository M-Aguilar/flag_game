Here are a couple javascript games.

Flag Game
This script is implemented on a Django based web application. It expects to remove elements with a "start" class.
It takes a csv file as input with each line containing two comma separated varuables. Each line corresponds to a specific country/territory.
<table>
  <tr>
    <th>
      Emoji
    </th>
    <th>
      Code
    </th>
    <th>
      Country/Territory Name
    </th>
    <th>
      SVG file path
    </th>
  </tr>
  <tr>
    <td>
      🇺🇸
    </td>
    <td>
      US
    </td>
    <td>
      United States
    </td>
    <td>
      united-states.svg
    </td>
  </tr>
</table>

Country Quiz
This script expects elements with the class "start" when initializing the setup and removes them.
A GeoJSON file is expected with a FeatureCollection of Feature:Countries. 
The GeoJSON that was used in this game was.
