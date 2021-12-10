# <h1>Seattle Public Libraries</h1>

[Link to project](Manhongg.github.io/geog495_final_project/index.html)

<h2>Project Description</h2>

My web application uses geodata from the City of Seattle GIS program that provides a comprehensive list of all Seattle public libraries to map and display the geographic locations of public libraries throughout the city. The map uses visual markers indicating the apporximate locations of each libraries, and allows users to click on the icon to zoom in closer to the locations of libraries in various neighborhoods around the City of seattle. The markers display information on the sidebar and in popup boxes stating the location and address of each library, allowing users to reference which neighborhoods have public libraries and how far they are from the user. The web application allows users to locate and browse all Seattle Public Libraries, indicating their locations and distance from the user’s current location using markers. 

<h2>Project Goal</h2>

For my project, I wanted to create a GIS web application that would show the locations of Seattle Public Library branches across the city. I felt like this would be a useful web application because many members of the community rely on public libraries for resources and information, especially low-income demographics who depend on public resources such as libraries for community gathering and accessing otherwise expensive materials.
As someone who used to frequent the library often with my parents, who instilled a habit of checking out books and DVDs from the library on an almost weekly basis, I grown a strong appreciation for the library and its crucial role as a community gathering palce and a source of free entertainment and learning for people who are frugal or cannot afford the luxury of paying for books and movies. 

For people and households that depend on public libraries or frequently visit them, this information can be useful in deciding which neighborhoods to live in and what routes to take to the nearest location. City officials can also use this information to gauge which neighborhoods are receiving adequate funding for public projects and which neighborhoods are lacking in community resources. Web applications that use public information to educate the community and demographics that might benefit from knowledge regaridng these reources will make a positive impact and also give nonprofit organizations and city officials insights on how and where to allocate resources in the future. 


<h3>Main Functions</h3>

**geojsonFetch()**

This function retreives the location data from a geojson file in the assets folder of my repository, and stores the information for future use in my web map and populates the sidebar display and popup boxes with the appropriate data. 

**buildLocationList()**

This function creates the sidebar display detailing all public libraries and their locations, adding an event listener to implement inetratcive features when the user clicks on a marker or popup display. 

<img width="1177" alt="web_application" src="https://user-images.githubusercontent.com/43800949/145516935-387662e1-e8f8-44d1-8455-ab616761e10e.png">

Link to dataset: https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::seattle-public-libraries/about

![image](https://user-images.githubusercontent.com/43800949/145508673-56390f3f-965b-4e40-955d-4c56d6158d0c.png)

<h2>Data Sources and Acknowledgements</h2>

My project repository is hosted on Github.

My web application was based on this template: https://docs.mapbox.com/help/tutorials/building-a-store-locator/

Applied libraries: Mapbox gl js

Mapbox style: https://www.mapbox.com/maps/dark




