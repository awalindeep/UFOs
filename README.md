# UFOs

_A JavaScript Interactive web-page_

## Overview of Project

### Purpose

The purpose of this project is to build a  **dynamic web-page**  that displays UFOs sightings information for upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon. There is a lot of data to display so adding filters to the table which let users to refine their search on more than one level is absolutely necessary.  
The web-page contains the following:

-   Interactive filters for searching criteria on date, city, country and shape.
-   Brief article and its summary.
-   An attention-grabbing header with a refresh-page button.
-   Visually appealing design of overall presentation of the data.

![head](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Resources/heading.png)
A snippet from the header of the webpage.

### Background

For this project I am using  **JavaScript**  as the primary coding language. JavaScript is a scripting or programming language that allows to implement complex features on web pages (1). It is a lightweight OOP (object-oriented programming language) also known as a front-end development language and is most commonly used as a part of web pages. JavaScript adds extra functionality and customization to web-pages in order to enhance user experience (2). Besides JavaScript I am also using the following to build the dynamic web-page:

-   The data for the table is stored in a JavaScript array.  [data.js](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Static/js/data.js)
-   The table is built by inserting  **JavaScript**  into HTML page.  [app.py](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Static/js/app.js)
- **HTML**  to build the webpage [index.html](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/index.html)
-   **CSS**  and  **Bootstrap**  to build and style the page  [style.css](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Static/CSS/style.css)
-   **Chrome Developer Tools**  to test the code.

##Resources

-   **Data Source:**  JavaScript list  [data.js](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Static/js/data.js)
-   **Software:**  VS Code and Chrome Developer Tools,
-   **Languages:**  JavaScript, HTML, CSS and Bootstrap 3
-   **Dependencies:**  D3

## Results

Raw data from JavaScript array is now displayed in a dynamic table where users can filter data on multiple criteria by  **date**,  **city**,  **state**,  **country**  and  **shape**  of UFOs sighting. In the filter input box is suggested text of how search criteria should be entered by user. For example, date should be entered in format as in 1/10/2010 – with forward slashes and without extra 0 before day and month. City, state and country should be entered in lower case.

![filter](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Resources/filter.png)

Dynamic multi-filter.

When user types desired criteria in multi-filter and then press enter the table displays only rows that matches the user input. From the picture below we can see only data that has been filtered based on the user input – that is --  Shape: circle


![Search](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Resources/search.png)

New table, displays only the results that matches the users input.

When resetting the filter, the user has two choices. User can either can clear input manually deleting input cell by cell or click the refresh button  _UFO Sightings_  that can be found at the top left corner of the page. After the filter is cleared, the user can use filter again.

![Reset](https://github.com/awalindeep/UFOs/blob/AwalinGHMAIN/Resources/reset.png)

Reset filter and refresh page button at the top left corner of the web-page.

## Summary

To build dynamic webpages that accept user inputs and visually adjust to reflect that interaction require quite a bit of work and patience. As I am pleased with the work, there is always room for improvement. At that opportunity, I would like to address some drawbacks and recommendations for further analysis.

### [](https://github.com/AndrejaCH/UFOs#drawbacks)Drawbacks

•  **All the data is displayed at once**  which makes the entire web-page quite lengthy.

•  **Reset button is too far away from the filter**  which is inconvenient, especially on the smaller screens, when user has to scroll up to reach the reset button and clear out the filter.

### Recommendations for further analysis

•  **Converting all input to lower case.**  Adding additional line of code that that would convert all letters to lower case from user input. In this case, the search criteria capabilities have much wider range and will improve user’s experience. For example, it wouldn’t matter if user types “CA” or “Ca” instead of “ca”, the code will still be able to process and find the results.

•  **Adding drop down-menu from the filter**. Sometimes users don’t know what exactly they are looking for and just exploring our web-page and its data. We could increase positive user experience by adding drop-down menu. In this case user won’t have to guess what options they have.
