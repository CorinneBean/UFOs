# UFOs
 Javascrript, Bootstrap, and UFOs

## Project Overview
This project demostrates the ability to build a dynamic webpage that allows users to filter the data to display information about UFO sightings. To allow customization of the data so that only the most relevant information is displayed several filters were created for the user to utilize. 

## Results

### Search Criteria Procedure
Below I have taken the liberty to break down the different search fields. Each field will automatically update the table as you enter in the filter criteria. You can filter each section individually or you can add multiple filter criteria to get the data that you want.

#### 1. Index page
[index.html](https://corinnebean.github.io/UFOs) is the initial html page. Clicking on the navbar at the top of the page will set all filters back to default.
![Index Page](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/Indexpage.png)

#### 2. Filtering by event date
![Date Filter](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/datefilter.png)

#### 3. Filtering by city
![City Filter](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/cityfilter.png)

#### 4. Filtering by country
![Country Filter](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/countryfilter.png)

#### 6. Filtering by state
![State Filter](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/statefilter.png)

#### 7. Filtering by state
![Shape Filter](https://github.com/CorinneBean/UFOs/blob/dd6427088ce4e4157e911534f95c71afda6a293f/Static/Images/shapefilter.png)

## Summary
- One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
- A way to address this would be to present drop-down lists including all filter values in place of the input fields.<br>
Each list would need to update after a parameter is selected in any filter.
- Including a button to clear the filters is also needed. The button would be located below the last filter.