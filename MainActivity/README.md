# Already Added, 
PLEASE READ
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


####By Deepak Nalla and David Chwatel


 



