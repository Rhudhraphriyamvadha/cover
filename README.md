# Ex.06 Book Front Cover Page Design
## Date:01.12.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
bookcover.html

<html>
    <head>
        <meta name="viewport" content="width=device=width, initial-scale=1.0">
        <style>

            .bookpage{
                width: 400px;
                height: 600px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(bg\ image.png);
                background-size: cover;
            }

            .insight{
                color: black;
            }

            .hrstyle{
                width: 130px;
                
            }

            .author{
                display: inline;
                position: relative;
                color: white;
                top: 250px;

                font-family: Georgia, 'Times New Roman', Times, serif;
                font-size: medium;
            }

            .booktitle{
                font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                font-size: large;
                text-align: center;
                position: relative;
                top: 40px;
            }

            .id{
                width: 400px;
                position: relative;
                top: 250px;
            }

            .pub{
                font-size: medium;
                color:black;
                position: relative;
                top: 250px;
                left: 100px;
            }

            .ed{
                color: black;
                font-size: medium;
                font-family: Verdana, Geneva, Tahoma, sans-serif;
                position: relative;
                top: 150px;

            }

            .subtitle{
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                font-size: small;
                position: relative;
                top: 50px;
                left: 30px;
            }

            .mypic{
                position: relative;
                top: 200px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;

            }
        </style>
        <title>BOOK COVER</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">STUDENT INSIGHT</div>
            <div class="hrstyle">
                <hr style="color: yellow;">
            </div>
            <div class="booktitle">
                <h1>FULL STACK DEVELOPMENT</h1>
            </div>
            <div class="subtitle">
                With React.js and Node.js using Visual Studio Code
            </div>
            <div class="mypic">
                <img src="my image.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>Rhudhra phriyamvadha K S</b></p>
            </div>
            <div class="pub">
               Learn the quick and easy way 
            </div>
            <div class="ed">
                <b>THIRD EDITION</b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-01 171145.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
