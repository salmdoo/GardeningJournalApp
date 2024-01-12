## Objective
* Show the list of Gardening user added
* Has function allow user add a new Gardening
* View Gardening details by clicking on a Gardening item on the list


## Screenshorts
| Screen | Screen | Screen |
|----------|----------|----------|
| ![Screenshot_20240111_214336](https://github.com/salmdoo/GardeningJournalApp/assets/118146780/93eaa5d4-da09-404e-a8aa-55211024f6e6) | ![Screenshot_20240111_215453](https://github.com/salmdoo/GardeningJournalApp/assets/118146780/36e2f1d9-1efd-4645-994b-203c5abc2bb7) |![Screenshot_20240111_215443](https://github.com/salmdoo/GardeningJournalApp/assets/118146780/55239ee3-1ba6-4ae1-a60b-e29b4ae9ae83) |



## How to build and run it
* Download source code from github
* Open the project by IDE
* Run and review the result
## Technique applied

* Navigation Structure:
Create a gardening app with at least three main screens: Home, Garden Log, and Plant Details.
Use the Navigation component to implement navigation between these screens.
Utilize a NavHostFragment for hosting the navigation graph.
 

* ViewModel and LiveData:
Implement a ViewModel for each screen to manage the UI-related data.
Use LiveData to observe and update the UI based on the underlying data changes.
Ensure that the ViewModel survives configuration changes.
 

* Room Database:
Create an entity class representing a plant with attributes like name, type, watering frequency, and planting date.
Implement a Room database to store and retrieve plant data.
Use a DAO (Data Access Object) to perform database operations.
 

* Coroutines:

Use coroutines to perform asynchronous operations, such as database queries.
Ensure that database operations run on a background thread to avoid blocking the main thread.
