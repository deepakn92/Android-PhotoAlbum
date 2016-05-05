#PLEASE READ
# YOU NEED TO PUT IN THIS SNIPPET OF CODE FOR THE PROGRAM TO WORK: THE FOLLOWING ASKS THE USER PERMISSION TO ACCESS THE GALLERY TO CHOOSE PHOTOS.
## PLEASE COPY AND PASTE THIS INFORMATION IN THE MAINACTIVIY FILE under the init() method  :
####
if (checkSelfPermission(Manifest.permission.READ_EXTERNAL_STORAGE)
                != PackageManager.PERMISSION_GRANTED) {
            requestPermissions(new String[]{Manifest.permission.READ_EXTERNAL_STORAGE},
                    MY_PERMISSIONS_REQUEST_READ_EXTERNAL_STORAGE);}
	}
#Also MY_PERMISSIONS_REQUEST_READ_EXTERNAL_STORAGE is an app defined constant, so in the variable decalarations above please copy and paste this:	
public static final int MY_PERMISSIONS_REQUEST_READ_EXTERNAL_STORAGE = 1;

#I AM WILLING TO ACCEPT A DEDUCTION OF POINTS FOR THIS, BUT PLEASE KINDLY ALLOW THIS TO BE ADDED INTO THE CODE. THANK YOU, BEST WISHES..

####By Deepak Nalla and David Chwatel

#####Features:

-Everthing works and all data is persistent, the app can be either closed or paused at any time.
- You can create as many albums as you'd like. Any album can be deleted or renamed when you are in the album view. If an album is deleted, its photos are deleted if they don't exist in any other album.
- Add a photo to an album from the Android Gallery or by using the Camera to take a picture. You can add photos to the storage folder in file explorer view in Eclipse.
- 2 tags can be added to any photo the full image activity. Only "Person" and "Location" tag types are allowed.
- A photo can be moved to a different album from the full image activity only if there is more than one album.
- Slideshow can be done from the full image activity, advancing to the next or previous photo in the album.
- Search can be done from the full image activity or the main activity. Searching allows for completion, and is done based on the tag value. If there are results, the matching photo can be displayed by tapping on the given result.
*To add photos to an album, you first need to have some photos in the Android Gallery on the device


