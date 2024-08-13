----------------------------
# spacex_modeling
----------------------------
This project is aimed to model space x data and make prediction for any successful landing of falcon 9. This infomation will be used by another company Space Y which is a compettior to spaceX to make more infomed decision on what to invest in. On averange spaceX landing take about $ 63 million where for other companies it consumes more than $ 165 million.Much saving is because spaceX can reuse the first/initial stage. So my main focus is to determine is the first stage will be a succes and if I am able to do so, them I can as well determine the cost of the whole process.

The first step is to web scrap and get data from spaceX api keys.
This are our objectives for the first mining:
(getting)
- Booster version from the rocket database
- Launch site and get, latitude, longitude, and the name
- Payload getting the mass kilograms and the orbit
- core(the outcome for landing). We will get the following data, type of landing, number of flights with the core, whether grids were used, whether the core we re-used, whether legs were used, landing pad used, block of the core( number used to separate version cores), number of times the specific core has been reused and finally serial of the core.
