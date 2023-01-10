# Coordinates
<img src="https://cdn-icons-png.flaticon.com/512/2179/2179254.png" alt="drawing" width="400"/>

# About
This code read a CVS file and return another one adding columns with geographic coordinates (Latitude and Longitude). Also there's a dinamic map plot by plotly. 
Obs.: The dataset was obtainded by a fake data generator website.

Project status: :heavy_check_mark: Concluded

# Index
:small_blue_diamond: [Challenge](#challenge)

:small_blue_diamond: [Features](#features)

:small_blue_diamond: [Prerequisites](#prerequisites)

:small_blue_diamond: [Plotly Map](#plotly-map)

:small_blue_diamond: [Author](#author)

:small_blue_diamond: [Contributions](#contributions)

# Challenge
Obtain geographic coordinates of people or companies descripted on a dataset. This code return Latitude and Longitude for each line of data, providing the visualization of them on a map. Here I used Plotly to show how to create a map on Python, but maybe it's more interesting to create on another softwer, like Power BI, that allows more creativity and possibility to create personalized tooltips. 

# Features
- Because dataset contain adresses from Brazil, we treated the zip code (CEP) column to leave it in a standardized format (xxxxx-xxx);
- If the API can not find the geographic coordinates (because of a type error on a column for example), returns the string "Erro"; 
- This project calculate the time of execution. By experimentation, a unique requisition takes between 0.6 and 1.1 seconds, also depending on computation capacity. On a large dataset, this code can take a long time;
- It's possible to get the geographic coordinates of others countrys!

# Prerequisites
Librarys required in this project:

- [Pandas](https://pandas.pydata.org/)
- [Requests](https://requests.readthedocs.io/en/latest/)
- [Time](https://docs.python.org/3/library/time.html)
- [Re](https://docs.python.org/3/library/re.html)
- [Geopy](https://pypi.org/project/geopy)
- [Plotly](https://plotly.com/python)

# Plotly Map
As example, take this screenshot of a map created under these codes:

<img src="Mapa.png" alt="Mapa"/>

# Author

[<img src="https://avatars.githubusercontent.com/u/109088916?s=400&u=0128dd8ac18d3e18783c4f52c5bb89578f12311f&v=4" width=115><br><sub>Bruno Cavalcanti Santos</sub>](https://github.com/BrunoSantos14)
    
# Contributions
Any doubts or ideas to develop this project you can contact me on email: bruno.canti.santos@gmail.com
