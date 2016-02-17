# Web-Design-Project

This is a simple website project creatd for COMP20030 Web Design 2014-2015 module. 

Information about the the content of the website 

**Name of the website:**  Discover Spain.

**Aim of the website:** To Promote and provide information about some popular holiday
destination. In this case I picked Spain.



I have selected three main cites in Spain
1. Madrid
2. Barcelona
3. Cordoba


The website contains a page for each city that have some basic information combined with
pictures of the main attractions in there , also I have included an information about the
transport system and 3 hotels along with a map of the city.


There are two pages also, "about.html" that have information about the aim & goal of the
website for the visitors and "contact_us.html " that have information for the visitors of the
website and how they can contact us.


**Tools used for building this site:**

1.Dreamweaver (for coding and designing)
2.Adobe illustrator/Photoshop (for logo design/icon)
3.Google map api (for maps)
4.Flexslider (for the slideshow in index.html)
5.HTML5, CSS3, JavaScript

**Website structure/design:**

since the website is about Spain, and the flag of Spain contains yellow and red color, I
have selected red and yellow color schema for this web site. You can see this in the logo
and the color of the hyperlinks.Web Design

Also, I have divided the website into header, main and footer. Header and footer section
of each page is the same, only the main part changes for each page. I have used the
same CSS code for each page by CSS class.

Here are some of the things I have used to build the site :

*hyperlinks of this site:*
as it stated before the color schema of the site is red & Yellow, the hyperlinks are red
but it changes to yellow once you move the mouse over it is used for mouse hover effect.

*Dropdown menu:*
I have used CSS code for designing the dropdown menu, CSS hover event to display and hide
dropdown menu.

*Flexslider:*

Flexslider is a popular and free JavaScript slideshow api based on JQuery (hence the jquery file).
I have integrated flexslidercss, jquery and flexsliderjs by following source code:

    <link href="flexslider/flexslider.css" rel="stylesheet">
    <scriptsrc="js/jquery.min.js"></script>
    <scriptsrc="flexslider/jquery.flexslider-min.js"></script>Web Design

In html, the div must be defined by flexslider class. And the images has to be under the tag.

    <div class="flexslider">
    <ul>
    <li><imgsrc="img/slider/san_sebastian.jpg" /></li>
    <li><imgsrc="img/slider/palacio.jpg" /></li>
    <li><imgsrc="img/slider/mezquita-de-cordoba.jpg" /></li>
    <li><imgsrc="img/slider/barcelona.jpg" /></li>
    </ul>
    </div>
    
   *Google map :*
I have used javascriptapi of Google map. At first I have used the following code to integrate the Google map api:

    <scriptsrc="http://maps.googleapis.com/maps/api/js"></script>
    <script type="text/javascript">
    function initialize() {
    varmapProp = {
    center:newgoogle.maps.LatLng(40.4167379,-3.714886),
    zoom:16,
    mapTypeId:google.maps.MapTypeId.ROADMAP
    };
    var map=new google.maps.Map(document.getElementById("googlemap"),mapProp);
    }
    google.maps.event.addDomListener(window, 'load', initialize);
    
    </script>

Then I defined a <div> tag by googlemap id to show the map on that div.

*Favicon :*
an icon associated with a website or webpage intended to be used when you bookmark the
web page. Web browsers use them in the URL bar, on tabs, and elsewhere to help identify a
website visually.
I made one( cropped the first letter from the logo) and I linked it to the pages using this code
<link rel="icon" href="img/icon.png">


**References:**

I do not own most of the materials in this site, all the pictures and the information about Spain
is from these sites:

1. https://www.wikipedia.org/

2. http://www.tourspain.org/

3. http://www.hotels.com/

4. http://www.spain.info/

5. http://spainguides.com/
