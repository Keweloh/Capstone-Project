# Capstone-Project

Introduction:

As a part of the IBM Data Science Professional Certificate, you will find in this post an overview of the final capstone project. Germany is one of the western European country with a varied landscape of rivers, forests, mountain ranges and beaches in the northern part of the country. It is the most populous country in the current member state of the European union. Berlin and Munich are two of the top three largest cities in Germany and there is significant amount of attrition of people from one city to the other every year. This project explores the neighborhoods in both Berlin and Munich on how similar and dissimilar they are based on the location data from Foursquare website. The aim of the project is to aid people who would like to move from one city to other and suggest where they should rent their new apartment in the respective city.

Data:

For this project, data from foursquare is used to analyze different neighborhoods in the above-mentioned cities Berlin and Munich. Venue data of these two cities will be analyzed to identify certain traits such as availability of schools, cafes, restaurants etc. to identify the neighborhoods. Regularly spaced grid of locations centered around a defined city center is used in this analysis to define the neighborhoods in Berlin and Munich as the official neighborhoods in both cities are sized very differently. The following data sources will be needed to generate the required information. • Geopy Nominatim: to extract the data for city center. Bundestag building for Berlin and Marienplatz for Munich. • With a fixed radius, the neighborhoods are generated algorithmically. Addresses of the above-mentioned city centers are obtained using geopy Nominatim reverse geocoding. • Using the Foursquare API, number of venues and their category in every neighborhood are obtained.

Disclaimer:

The data that is used in this project for Germany might not be as extensive as it is compared to that of the U.S and the analysis therefore might not be comprehensive.
