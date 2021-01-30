# FyndARv0.0
AR application with sceneform made with android studio.
FyndARDemo: 

1. Open project and import into Android Studio. 

2. Search for LandActivity.java (which is our main Activity) using Shift+F (com.fynd.ardemo). 

3. In the LandActivity, there are the following:
	- A 'listView', which is the menu for our app, consisting of hardcoded menu items.
	- A 'locationTextView' which controls the location (using Geocoder). 
	- A 'getlocationButton' which initiates the location retrieval. 
	{LOCATION DOSEN'T CURRENTLY WORK ON ACTUAL DEVICES}. 
	- A String 'fullAddress' for the current address. 

4. The 'getlocationButton.setOnClickListener(new View.OnClickListener()' method is used 
to get the current location and show the location and listView when the location is successfully found
(the 'addOnSuccessListener()' does this, inside the try/catch block.

5. The listView has hard-coded items based on the models we have imported and show the corresponding item
if the value is clicked. The listView has an adapter that has items in the 'string.xml' file.

6. The AugmentedActivity(food-name).java files have the logic for the AR objects. 

7. 'requestLocationPermission()' method asks for permission to use location. 

8. Our models live inside the 'sampledata' directory and the res/raw directory (.obj, .mtl, and .sfb files)
which are imported using Google Sceneform SDK plugin (can be installed by searching for plugins in Settings > Plugins > Browse Repository Plugins).  

9. Layout files are in the res/layout folder. 
