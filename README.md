# python-api-challenge

The relevant code for both WeatherPy and VacationPy can be found within the WeatherPy folder in the python-api-challenge repository on GitHub. The relevant figures can be found in the output_data folder in the  python-api-challenge repository on GitHub.

All work was done independently with occasional help from the Xpert AI tool and past class activities on GitLab.

The WeatherPy portion of the assignment tested past knowledge of knowing how to code scatter plots, linear regressions, calculate r values and interpret all of the information. The additional knowledge was knowing how to access information stored in a particular API using api keys, end point urls, requests.get() and .json() - these allowed us to visualize the relevant information stored in the APIs which was then used for the plots and analysis.

The VacationPy portion of the challenge, much like the WeatherPy, tested our ability to extract data stored in a particular API. In turn, the relevant bits allowed us to produce maps. Furthermore, using longitude and latitude data obtained from Geoapify API, we automated a search of the closest hotel to the particular coordinates in a few cities. This was possible with the use of api key, appropriate parameters, a for loop and the base url. Then, using requests.get() and .json(), we visualized this data. Finally, with the use of try and except, we ensured that our automated search did not crash in instances where no hotel was found in the set parameters.