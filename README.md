# UFOs
![ufo](https://user-images.githubusercontent.com/36451701/143145116-1d5e0162-65b8-4c0f-93fa-287d327d34f4.png)

## Project Overview:
This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.

### Project Challenge:
*The challenge is to provide a more in-depth analysis of UFO sightings data by allowing users to filter by multiple criteria.  The data is difficult to analyze when viewing it in its complete form on the webpage.  Adding multiple filtering criteria will allow the user to narrow down their search results.  To accomplish this, additional filters for city, state, country, and shape will need to be created using JavaScript, HTML, and bootstrap.  The end result will be a dynamic webpage with UFO sighting data that user can narrow down to their specific search criteria.*

### What I'm creating:
1. Deliverable 1: Filter UFO Sightings on multiple criteria
2. Deliverable 2: A written report on the UFO analysis

### Project Resources:
- Data Sources: UFO sighting data provided

- Software:
    - Python 3.8.5
    - MacOs Catalina Version 10.16.7
    - Jupyter Notebook 6.1.4
    - Visual Studio Code 1.57.1
    - BootStrap 4.4
   
## Project Results:
### Link to UFO Sightings webpage - [https://dsupps.github.io/UFOs/](https://dsupps.github.io/UFOs/)

The index landing page is interactive and has the ability to filter search results by date, city, state, country, and/or shape. The user can choose one up to all five filters at once.

<img width="1280" alt="index1" src="https://user-images.githubusercontent.com/36451701/124338132-306bea00-db74-11eb-80f0-c545c5c5a8aa.png">

### Filter by date:
The user can filter by the event date. In the box underneath "Enter Date", the user can input any date available in the dataset and just the events recorded on that date will display. In the example shown, the user selected the date of 1/13/2010.   

![date](https://user-images.githubusercontent.com/36451701/124338146-45487d80-db74-11eb-9860-ff76cca31a5b.png)

### Filter by city:
The user can filter by city.  In the box underneath "Enter the City", the user can input any city available in the dataset and just the events that occurred in that city will display. Here the user has chosen the city of Port St.Lucie.

![city](https://user-images.githubusercontent.com/36451701/124338159-5beed480-db74-11eb-83f1-285bf31e71b7.png)

### Filter by state:
The user can filter by state.  In the box underneath "Enter a State", the user can input any state available in the dataset and just the events that occurred in that state will display.  Here the user has chosen Florida. 

![state](https://user-images.githubusercontent.com/36451701/124338246-c142c580-db74-11eb-80ca-bca6f9c8b6ba.png)

### Filter by country:
The user can filter by country.  In the box underneath "Enter a Country", the user can input any country available in the dataset and just the events that occurred in that country will display.  Here the user has chosen the US.

![country](https://user-images.githubusercontent.com/36451701/124338180-7163fe80-db74-11eb-92e3-0e1f83ee6eff.png)

### Filter by shape:
The user can filter by shape. In the box underneath "Enter a Shape", the user can input any shape of object available in the dataset and just the events that contain that shape will display.  Here the user has chosen the shape of a spehere. 

![shape](https://user-images.githubusercontent.com/36451701/124338188-7cb72a00-db74-11eb-8fd4-60e5526f4cf9.png)

### Filter on multiple criteria:
The user can also filter on multiple criteria.  The can choose up to five multiple criteria.  

![multiple](https://user-images.githubusercontent.com/36451701/124338210-8f316380-db74-11eb-9cf4-1d409475b5f2.png)


## Challenge Summary:
The UFO Sightings: Fact or Fancy? is now a dynamic webpage that provides users with data about UFO sightings and the ability to create specific search criteria if they so choose.  To get back to the default filter search, all the user has to do is clear the search criteria and hit return or refresh the page. 

There is one obvious drawback to the site.  The user must know the exact filter search text formats to pull up the data they are looking for. If the wrong format is used, the table will not display the specific data the user is looking for. 

One recommendation would be the ability for search to work using upper or lower case text.  Currently, if the user types in "AZ" instead of "az" for the state of Arizona, nothing will come up.  The user might mistake the empty results and think nothing is available for Arizona even though there are multiple events that show up when "az" is typed in. 

Another recommendation would be the functionality for the user to downloand the dataset at the click of a button. 
