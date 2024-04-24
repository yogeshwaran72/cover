# Ex.06 Book Front Cover Page Design
## Date:7.4.24

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
book.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 255, 60);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(mustang.avif);
            background-size: cover;
        }
        .insight{
            color: rgb(0, 255, 60);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(0, 255, 60);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(0, 255, 60);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(0, 255, 60);"></div>
            <div class="booktitle"><h1>MUSTANG GT 2024</h1></div>
            <div class="subtitle">
                
                
                USER MANUAL</div>
            <div class="mypic"><img src="my image.jpg" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(0, 255, 60);"></div>
            <div class="author"><p><b>BY YOGESH A</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>
```

## OUTPUT:
![Screenshot 2024-04-24 141126](https://github.com/yogeshwaran72/cover/assets/153492924/5bd7444c-5ca1-4887-905d-e4f27169370d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
