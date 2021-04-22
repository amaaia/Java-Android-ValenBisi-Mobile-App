# JAVA-ANDROID: ValenBisi Mobile App
Development of a mobile app for Android devices about Valenbisi, the bike rental system of the city of Valencia.


The app will allow users to check the status of the different bike stations and to create incident reports. It will use the services of the City Council of Valencia to retrieve data of Valenbisi bike stations. This query will initially be carried out using a JSON file that can be requested from the web service of Valencia’s open data website. However, in the first part, we will work with internal files in order to simplify: the JSON file with the complete list of bike stations will be downloaded and copied to the project. On the list of bike stations, we will show the information about each of them. Next, we will create a local database that will allow the creation of new incident reports associated with each of the bike station. Finally, we will perform the query about the Valenbisi bike stations through the web service, in order to display real-time data to our users. This project will be developed using Android Studio. 

# Goals:

The goals of the project are the following:
- Work with JSON format files.
- Work with Activities and Intents.
- Work with ListView and Adapter.
- Develop layouts to display the different elements of the user interface.
- Create a local SQLite database.
- Manage databases.
- Work with HTTP services by using JSON.
- Work with data from sensors.
