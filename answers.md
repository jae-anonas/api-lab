##### Task #1: Find the api call that allows you to search for all images of "cats".

API Call: 
https://api.flickr.com/services/rest/?api_key=bfbf7f7e955befd2d66e59576a9b1697&text=cats&method=flickr.photos.search&format=json

##### Task #2: Find the api call that allows you to search for all images from "Charlotte, North Carolina.

API Call: 
https://api.flickr.com/services/rest/?method=flickr.photos.geo.photosForLocation&api_key=fdd8b76922109413d9c6f273fbad3bc4&lat=35.2271&lon=-80.8431&accuracy=11&format=json&nojsoncallback=1&auth_token=72157671815653036-41a610453449fee4&api_sig=6235ce644dd849ae3f9e64244f2a0644

##### Task #3: Get all of the comments for any photo.

API Call:
https://api.flickr.com/services/rest/?api_key=bfbf7f7e955befd2d66e59576a9b1697&photo_id=[id]&method=flickr.photos.comments.getList&format=json

##### Task #4: Search for a list of all the photos in your current latitude and longitude.

API Call:
https://api.flickr.com/services/rest/?method=flickr.photos.geo.photosForLocation&api_key=fdd8b76922109413d9c6f273fbad3bc4&lat=40.740104&lon=-73.990439&accuracy=&format=json&nojsoncallback=1&auth_token=72157671815653036-41a610453449fee4&api_sig=542377986aeee6ff6c3244ee796503b2
