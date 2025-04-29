# Ex04 Places Around Me
# Date:29-04-25
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

# CODE
~~~
  <!DOCTYPE html>
  <html lang="en">
  <center>
  
      <head>
          <title>Tamil Kingdom </title>
      </head>
      <style>
          .para {
              border: 2px solid black;
              border-radius: 30px;
              padding: 40px;
              width: 400px;
              font-size: large;
              margin-top: 50px;
              font-style: oblique;
              font-weight: 700;
              background-color:sandybrown;
             
  
          }
          
              body{
                background-image: url('background.webp');
                background-repeat: no-repeat;
                background-attachment: fixed;
                background-size: cover;
              }
            
            
  
          .image {
              
              width: 600px;
              padding-right: 50px;
          
              
          }
          nav{
              padding: 6px;
             background-color:lightgray;
            color: rgb(15, 12, 96);
            border-radius: 10px;
            width: 1300px;
          }
      </style>
  
      <body >
          <nav>
          <h1>Tamil Kingdoms</h1>
          </nav>
  </center>
  <table>
      <td>
          <img class="image" src="tamilkingdom.png" usemap="#kingdoms" alt="Map Image"
              style="max-width: 100%; height: 500px;">
      </td>
      <td>
          <div class="para">
              <P>The Tamil kingdoms of southern India, including the Cheras, Cholas, and Pandyas, represent a rich
                  tapestry of history, culture, and governance. These ancient dynasties flourished between the early
                  centuries of the Common Era and the medieval period, each contributing uniquely to Tamil culture and
                  society.<br></P>
              <p>These kingdoms were known for their robust trade networks, both inland and overseas. They engaged in
                  commerce with regions as far as the Roman Empire, Southeast Asia, and beyond, exporting goods like
                  spices, textiles, and pearls. This trade not only enriched the kingdoms economically but also
                  facilitated cultural exchanges.<br></p>
              <p>The Tamil kingdoms played a crucial role in shaping the historical and cultural landscape of southern
                  India. Their legacies continue to influence modern Tamil culture, language, and identity, making them an
                  integral part of India's diverse heritage.</p>
          </div>
      </td>
  </table></center>
      <map name="kingdoms">
  
          <area shape="poly" coords="411,246,374,354,529,375,628,351,613,234"  title="Cholanadu" href="C:/Users/admin/Desktop/html%20agilan/cholanadu.html">
           <area shape="poly" coords="202,387,185,580,245,601,321,580,360,510,477,462,514,387,378,375,377,379,378,375" title="pandyanadu" href="C:\Users\admin\Desktop\html agilan\pandiyanadu.html">
          <area shape="poly" coords="304,76,239,194,33,220,178,373,351,354,353,267,436,221,399,127" title="Kongunadu" href="C:\Users\admin\Desktop\html agilan\kongunadu.html">
              
              
      </map>
  
      <body>
  
      </body>
      </body>
  </center>
  
  </html>
~~~
# OUTPUT
![Screenshot (97)](https://github.com/user-attachments/assets/4c93741f-f127-4544-a460-ae7ac99b1bef)
![Screenshot (98)](https://github.com/user-attachments/assets/c1d5a4cf-f09c-44b5-a593-7d1efed9a03b)
![Screenshot (99)](https://github.com/user-attachments/assets/ec06b71a-5729-4a4c-8d0e-ec1d03728120)
![Screenshot (100)](https://github.com/user-attachments/assets/59b6dc97-5424-455d-94d5-0c1efe878665)


# RESULT
The program for implementing image maps using HTML is executed successfully.
