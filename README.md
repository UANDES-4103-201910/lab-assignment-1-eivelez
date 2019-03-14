# lab-assignment-1
Base project for lab assignment 1



Step 1, Open webpage in Chrome:
DONE


Step 2, Activate Developer tools:
DONE


Step 3, Analyze the elements tab structure:

We can see how the whole page has a container structures called tags where you can go inside from the general to particular items.
For example we have the body, and inside the body the center tag, inside a table tag, inside that table we can see "tbody", inside there two kind of classes (spacer and athing)
needless to explain what them do. Every 'athing' has other internal structures like the index number, up-pointing triangle, and title that we can clearly see at the page.
Talking about the title, at the moment we only have seen where it should be, but if we continue opening "containers" we can see text like this: 
..<a href="https://www.nytimes.com/interactive/2019/03/13/world/boeing-737-crash-investigation.html" class="storylink">Why Investigators Fear the Two Boeing 737s Crashed for Similar Reasons</a >
This is the instruction to what show in the title class predefined space, and where to be redirected if we click. how this text should look like  (color, behaviour, size, font, etc) its also written in this
element tab window.
Just to add, we can see how the code gramatic to open and close something its <something> elements </something>
Little experiment: i changed the tab colour from <td bgcolor="#ff6600"> to <td bgcolor="#00ffd0"> (from orange to cyan), to experience how this code affects the page design.


Step 4, Analyze the sources tab:

At first sight we can see that files are downloaded in a logical orden of importance. First the main content  (index) , then the js (functions)  and css (visual instructions). These are the downloads of the codes we saw before in the elements tab.
For example in the elements tab here #<script type="text/javascript" src="hn.js?stXbi7LCyutClfTUMe1b"></script># is the html code part that execute the .js from the downloaded js that apears in source as hn.js?.....
At the end the gifs for the browser tab, and a couple of other visuals that i guess are there because image weights more than textcode
so to optimize low speed conections you can prioritize the content. (nothing worse than try to see a page's text and get first the ads and images. Anyway the image position and details of how it
should behave exist before the image gets downloaded,when it doesnt download correctly appears the  classic error from missing image that only appears "imageName.jpg" in text)

Step 5, XHRequest:
I tryed several timer refreshing the page but never appeared a xhr-type file, but i tryed pressing some buttons, links to other pages, using the search bar at the bottom of the page
and there appeared some cases. I looked for XHR in google and found that its basically an APi to make HTTP/HTTPS request to a web server. Its used a lot on dynamic pages to avoid constant refreshing of the whole page.

Step 6, Security Certificate:
The connection to this site is using a valid, trusted server certificate issued by COMODO RSA Domain Validation Secure Server CA.
Expiration date: 21/08/2019.
https://www.comodo.com/about/comodo-agreements.php
this certificate guarantees:
-the identification of a remote device
-proves it identification in front a remote device
-1.3.6.1.4.1.64xx.x.x.x.x.x. (dont know what its this)
-2.23.1xx.x.x.x (nor this)
 
