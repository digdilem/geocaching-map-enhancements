# geocaching-map-enhancements
A modified version of James Inge's Geocaching Map Enhancements

<img width="369" height="94" alt="image" src="https://github.com/user-attachments/assets/4535a761-4dd4-4456-9a26-b073f2b187d0" />

Between 2011 and 2018, James Inge created and updated a small Userscripts tool that greatly enhanced the Geocaching map at https://www.geocaching.com/map/ by adding a small overlay with some incredibly useful tools. 

These tools gave mapping details, allowing you to draw a route and gave its distance, as well as letting you save it. It also did postcode and address lookup, coordinates, hid all caches and a number of other tweaks. 

I don't know what happened to James, and his website at http://inge.org.uk is no longer working, so I believe this script to be abandonded. 

Whilst it still works in functionality, the sprite file that it relied upon for its icons disappeared as Groundspeak updated their systems, making it difficult to see what the icons did. 

I've therefore adapted this to use inline tabler svg icons, making the buttons useful again. 

I can't offer support on this script, but am sharing it if anyone does want to use it.

#### Notes:

- This only works on the original geocaching map at https://www.geocaching.com/map/
- It requires [Userscripts](https://www.tampermonkey.net/scripts.php?locale=en) to be installed as a browser extension. Then this file can be loaded into that, and on reloading the map it should show up in the bottom left corner.
- To fix an existing installation, simply paste this script over the existing one in Userscripts and click File -> Save
