# Create simple extension for Google Chrome
## Structure
The structure is very light and require 3 files:
- index.html
- function.js
- manifest.json

### index.html
In this file you can design your plugin using the tecnology that you prefer.
In this example there are a card that show some weathere data of Ferrara City.

### function.js
Here you can write your own script and customize the data you will provide to the user. In this case we used the weather-api
from https://rapidapi.com (https://rapidapi.com/weatherapi/api/weatherapi-com/)
and provide information about:
<li>
Temperature
</li>
<li>
Description of current condition
</li>
<li>
Humidity
</li>
<li>
Precipitations in mm
</li>

Note thate you can provide the information you want, according to the api response. 

### manifest.json
This file is an important configuration file used fom google chrome to define your extension info.
It must be placed in the root of your project.
Here some documentation about that: https://developer.chrome.com/docs/extensions/mv3/manifest/