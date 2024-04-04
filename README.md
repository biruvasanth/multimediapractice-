img> tag is empty becz it dont have closing tag but having two required attributes 
src attribute is contain the path or url of the requird img

if we have required img file("images.jpg") in  where index.html file exist  same as where you are using img tag use following mtd 
img src="images.jpg" alt="refresh">

if we have required img file in another folder use following mtd (and mentioned another folder should be in where index.html file exists)
img src="anotherfolder name\images.jpg" alt="refresh"> 




alt attribute

specify a alternative text for img 


style attribute 
style ="width:80px;   height:"50px" ;   "



<--links.html-->

Hyperlinks are defined using the a> tag. 
The a> tag has two attributes. 
The first attribute of the  a> tag is the href(URL address) attribute, which indicates the link's destination. 
The second attribute is the link text. It’s the part that will be visible to the user of the website. 
By clicking on the link text, the user will be sent to the  abov specified URL address.

by default when user clicks the  linktext it will display the linkedpage   in the current window
so if  we want to display the linkedpage   in the new window we have to use target attribute
 