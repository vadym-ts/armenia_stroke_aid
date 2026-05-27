# armenia_stroke_aid
# Armenia Stroke Aid Accessibility Map

QGIS-based analysis of travel-time accessibility to acute stroke care in Armenia.

This project explores how quickly patients can potentially reach specialized stroke treatment using a routable OpenStreetMap road network and travel-time accessibility modeling.

The analysis focuses specifically on the 6 hospitals participating in Armenia’s dedicated stroke treatment program, rather than all hospitals in the country. These centers were selected because acute stroke treatment is highly time-sensitive, and outcomes depend heavily on reaching appropriate care within critical therapeutic windows — often referred to as the “golden hour”.

Travel-time analysis was performed using a road network with estimated speeds assigned by road type. Areas located more than 3 km from the mapped road network were masked to avoid overinterpretation in sparsely connected mountainous terrain.

The resulting map represents estimated ideal travel time under normal conditions and does not account for dispatch delays, traffic, weather, or other operational factors. In some remote regions, real-world patient transport may also involve mixed solutions, including occasional air transport.

The analysis highlights notable regional differences in accessibility to specialized stroke care across Armenia.

All spatial analysis, preprocessing, and cartographic design were completed in QGIS using OpenStreetMap data.

This project was created as an exploratory healthcare GIS and cartography study focused on emergency care accessibility and travel-time modeling.

## Disclaimer

This project is intended for research and visualization purposes only and does not represent operational emergency routing or real-world ambulance performance.
