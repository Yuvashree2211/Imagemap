# Ex04 Places Around Me
# Date:21-10-2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE:
```
image mapping.html

<!DOCTYPE html>
<html>
    <head>
        <center>
        <title>Image Mapping</title>
    </center>

   </head>
    <body>
        <CENTER>
        <H1 style="font-family: Verdana, Geneva, Tahoma, sans-serif;">Image Mapping</H1>
        <h1>YUVASHREE (24900809)</h1></CENTER> 

        <img src="map.png.png" title="yuvas" alt="Diary" usemap="#mapping">

        <map name="mapping">
            <area shape="poly" coords="600,324,702,315,786,342,789,385,771,427,662,420" title="" href="file:///C:/Users/yuvas/OneDrive/Documents/timetable/im2.html">
            <area shape="poly" coords="889,73,925,81,941,121,907,139,872,112,867,85" title="" href="file:///C:/Users/yuvas/OneDrive/Documents/timetable/im.html">
            <area shape="rect" coords="1531,523,1378,490" alt="Ractangle" href="file:///C:/Users/yuvas/OneDrive/Documents/timetable/im1.html">





        </map>
    </body>
</html>


im.html
<!DOCTYPE html>
<html>
    <body>
        <center>
            <h1 style="font-size: larger;">LAPTOP</h1>
            <img src="laptop.jfif" title="laptop" alt="Little" usemap="#mapping" height="400" width="400">
        </center>

        <map name="mapping">
            <center>
            <H1>Advantages of Laptop:</H1></center>
           
<h3>
Mobility:
</h3>
<p style="padding-left: 40px;">
    ⭐The main advantage of a laptop, as compared with a stationary computer, is its mobility. <br>⭐The lightweight, compact size, the built-in battery within the laptop allowing it to simply move from one place to a different one. 
        </p>
        <h3>Finished product:</h3>
            <p style="padding-left: 40px;"> ⭐The laptop is straightforward to use without any additional devices. <br>⭐It’s everything like its own keyboard, built-in mouse (touchpad), built-in speakers, built-in microphone, many laptops have a built-in camera.</p>
            <h3>Internet access: </h3>
            <p style="padding-left: 40px;">⭐Internet access is the second advantage for the increase in demand for the laptop because it provides the power to access the web through wireless technology.</p>
            <center>
            <h1 style="font-family: 'Times New Roman', Times, serif;">Disadvantages of Laptops:</h1>
        </center>
        <h3>Frequent Upgrades:</h3>
        <p style="padding-left: 40px;">⭐The laptops are difficult to upgrade thanks to their integrated design. <br>⭐The sole parts which will be upgraded are hard disc and memory as these are the sole parts that are accessible to the user.<br> ⭐It’s very difficult to repair it. </p>
        <h3>Higher price :</h3>
        <p style="padding-left: 40px;"> ⭐The laptops are costly as compared to PC, because the smaller components required by the laptop come costly.</p>
        <h3>Difficulty in customization:</h3>
        <p style="padding-left: 40px;"> ⭐The laptop doesn’t offer an option for personalization consistent with one’s requirements.<br> ⭐The laptop only gives access to the computer’s memory and disk drive.<br> ⭐The opposite components like processors, graphics cards, and cooling systems aren’t easy to access and replace.</p>
  

    </body>
</html>


im1.html
<!DOCTYPE html>
<html>
    <body>
        <center>
        <h1>BOOK STALL📚</h1>
        <img src="bookstall.jfif" title="gold" alt="sel" usemap="#mapping" height="350" width="400">
    </center>
    <map name="mapping">
     
    </map>
        <h2>DESCRIPTION:</h2>
        <P style="padding-left: 40px;">⭐Libraries can vary widely in size and may be organised and maintained by a public body such as a government, an institution , a corporation, or a private individual.<br>⭐In addition to providing materials, libraries also provide the services of librarians who are trained experts in finding, selecting, circulating and organising information while interpreting information needs and navigating and analysing large amounts of information with a variety of resources. <br>⭐The area of study is known as library and information science<br>

            ⭐The library's clientele and general services offered vary depending on its type: users of a public library have different needs from those of a special library or academic library.<br>
            ⭐ Libraries may also be community hubs, where programmes are made available and people engage in lifelong learning. <br>
            ⭐ Modern libraries extend their services beyond the physical walls of the building by providing material accessible by electronic means, including from home via the Internet.
        </p>
    </body>
</html>


im2.html
<!DOCTYPE html>
<html>
    <head>
        <title>
            GARDEN
        </title>
    </head>
    <body>
        <center>
        <h1>GARDEN</h1>
        <img src="gardening.jfif" alt="flowers" usemap="#mapping" title="trends" height="400" width="500">
    </center>
    <map name="mapping">
     
    </map>
    <h3>DESCRIPTION:</h3>
    <p style="padding-left: 40px;">
        ❤️Gardening is the process of growing plants for their vegetables, fruits, flowers, herbs, and appearances within a designated space.<br>❤️Gardens fulfill a wide assortment of purposes, notably the production of aesthetically pleasing areas, medicines, cosmetics, dyes, foods, poisons, wildlife habitats, and saleable goods. <br>❤️People often partake in gardening for its therapeutic, health, educational, cultural, philosophical, environmental, and religious benefits.<br>
        ❤️Gardening can be difficult to differentiate from farming.<br> ❤️They are most easily differentiated based on their primary objectives. <br>❤️Farming prioritizes saleable goods and may include livestock production whereas gardening often prioritizes aesthetics and leisure.<br> ❤️As it pertains to food production, gardening generally happens on a much smaller scale with the intent of personal or community consumption.<br> ❤️It is important to note that there are cultures which do not differentiate between farming and gardening.<br> ❤️This is primarily because subsistence agriculture has been the main method of farming throughout its 12,000 year history and is virtually indistinguishable from gardening.
    </p>
    </body>
</html>


```
# OUTPUT:
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)




# RESULT
The program for implementing image maps using HTML is executed successfully.
