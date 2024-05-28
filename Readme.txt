=========================================
Dataset characteristics
=========================================	
day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
const              0.1671      0.027      6.245      0.000       0.115       0.220
yr                 0.2382      0.008     29.240      0.000       0.222       0.254
workingday         0.0565      0.011      5.104      0.000       0.035       0.078
atemp              0.3845      0.038     10.096      0.000       0.310       0.459
windspeed         -0.1473      0.025     -5.793      0.000      -0.197      -0.097
dec               -0.0648      0.018     -3.520      0.000      -0.101      -0.029
feb               -0.0443      0.022     -2.019      0.044      -0.087      -0.001
jan               -0.0814      0.022     -3.762      0.000      -0.124      -0.039
may                0.0193      0.018      1.096      0.274      -0.015       0.054
nov               -0.0565      0.019     -2.959      0.003      -0.094      -0.019
sep                0.0718      0.016      4.426      0.000       0.040       0.104
Light_snowrain    -0.2971      0.025    -12.095      0.000      -0.345      -0.249
Misty             -0.0818      0.009     -9.431      0.000      -0.099      -0.065
summer             0.0950      0.018      5.259      0.000       0.059       0.130
fall               0.0728      0.021      3.433      0.001       0.031       0.115
winter             0.1539      0.018      8.645      0.000       0.119       0.189
Wed               -0.0218      0.012     -1.894      0.059      -0.044       0.001
Mon    