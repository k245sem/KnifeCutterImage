# KasemKnifeCutter
What is KasemKnifeCutter?
-> It is a library to manage large Bitmap efficiently! 

How and Where to use?
-> This can be only used if you are displaying image into recyclerview. As recycler view freezes the UI when it has High Quality images. So to prevent this, KasemKnifeCutter Library can resize the image into recyclerView and prevent OutOfMemoryError

This is the method to use it:   
	
First add maven repositories:
maven { url 'https://jitpack.io' }

Then add this dependency:
implementation 'com.github.k245sem:KnifeCutterImage:1.0823'

Then to your JAVA file, use like this:
KasemKnifeCutter.decodeSampleBitmap(getResources(), resId, 100,10)
First argument getResources()
Second argument The image in the form of Integer (int)
Third argument The desired width of the image
Fourth argument The desired height of the image

and you are awesome! Thanks, Kasem S.M
Check this project on Jitpack.io -> https://jitpack.io/#k245sem/KnifeCutterImage/1.0823
For any queries, DM me on instagram -> https://www.instagram.com/k245sem 

		
