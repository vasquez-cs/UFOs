# UFOs
## Overview of Project: Explain the purpose of this analysis.

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings. She thought she could achieve this by allowing users to filter for multiple criteria at the same time. In assisting her, I added table filters for the city, state, country, and shape of UFOs.

### Results: 

<img src="https://user-images.githubusercontent.com/107224632/187095932-18987dd8-1304-42a5-b168-3dc890d62b2a.png" width=55% height=45%><br />
*Figure 1: Page header and article*<br />

As shown in figure 1 above, once on the page, a visitor will view that they are greeted by the page header followed by the article title and article, side by side. Figure 2 below shows the 5 filters on the left side and the data on the right.

<img src="https://user-images.githubusercontent.com/107224632/187098580-3f8b9594-cb78-4e5c-aa9a-21642718ce57.png" width=55% height=45%><br />
*Figure 2: Filters and data*<br />

The search filters are extremely useful and are great to narrow down the number of cases based on the incident data. If the end user has a city they want to focus on, they would enter the city name in lower case letters. Once the city name has been entered, the user would click anywhere outside the field. Another shortcut is to hit the "enter" key on their keyboard. This action will trigger the fitering to occur as show in figure 3 below. 

<img src="https://user-images.githubusercontent.com/107224632/187099070-06dfebc9-38ed-4874-999a-7492c874e022.png" width=55% height=45%><br />
*Figure 3: Filtered state data*<br />

The same steps would be done to filter the dataset by date, city, country or shape of UFO. If the filters need to be reset, the webpage can be refereshed or data cleared from the filter text boxes.

### Summary: 

A drawback of this design is that there isn't help text available. While the fields have stand-in data, there isn't further instructions that tell the user of the idiosyncrasies that the filters require to pull data. An example is the that if only a year is entered, the filter won't return results even if the year is available as part of a record's full date. For all text based filters, if any capitalization is entered the filters won't pull available data. The simple solution to this is to allow the filters to have more flexibility when searching for data. A stop gap while that fix is investigated and tested is to provide help text as captions under the filters.
