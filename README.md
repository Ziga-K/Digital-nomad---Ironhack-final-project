# Digital Nomad - Cities
## A Data Analytics Insight

#### Final project as a student with IronHack's Data analyst bootcamp

<img src="https://www.backblaze.com/blog/wp-content/uploads/2019/10/blog-rv-laptop.jpg" width="80%"></img>

***The Inspiration...***

While I was envisioning what my path would be after finishing the Ironhack's bootcamp I came across a website that seemed to a great source, an inspiration for thousands of expats to use and make decision on their next big destinations. 

Made me curious on what makes a city attractive to live in for expats... and if any insight can be done through data analytics. 


## Main Objectives:

- Use webscraping to get a dataset from nomadlist.com.

- Use some of [Nomadlist.com](https://nomadlist.com) data for insight on whats makes cities attractive for expats, either for visit or live in. 

- Build machine learning model to predict the city rank and possibly a city reccomendation code - this part is work in progress, would be explored and added later on...

## Overall Steps:

- Webscraping with Python and [Selenium](https://selenium-python.readthedocs.io) - See 1.nomadlist_scrape file.

- Build, clean and manipulate data into a dataframe with [Pandas](https://pandas.pydata.org) - see 2.clean_loc_data file.

- Getting location data with [Geopy](https://geopy.readthedocs.io/en/stable/.) and [Pycountry](https://pypi.org/project/pycountry/).

## Result:

- Please see Insights from the project in the [presentation](https://docs.google.com/presentation/d/12Rw1mWf9zF2CjiJ1xwlzN7AaMWJrP7ubtLV1PqpfMHs/edit#slide=id.p).

- Visuals as from the [Tableau book](https://public.tableau.com/app/profile/ziga.k./viz/Nomad_Cities/Story1?publish=yes).

- City rank prediction model(s) can be found in file ML_predict.
As mentioned above is work in progress still, although a data as is has been used to build the initial model. A high score of 0.98 has been observed with LinearRegression model.

