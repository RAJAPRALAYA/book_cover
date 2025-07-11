# Ex.06 Book Front Cover Page Design
# Date:25.04.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
CODE
```
<!DOCTYPE html>
<html>
<head>
  <style>
    /* Body with solid background color and modern font */
    body {
      background-color: #282c34;
      color: #ffffff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0 100px;
    }

    /* Main header */
    h1 {
      text-align: center;
      font-size: 60px;
      color: #61dafb;
      margin-top: 50px;
    }

    hr {
      border: none;
      height: 2px;
      background-color: #61dafb;
      width: 80%;
      margin: 20px auto;
    }

    p {
      text-align: center;
      font-size: 40px;
      font-weight: bold;
      color: #f0db4f;
    }

    .direct {
      font-size: 28px;
      background-color: #3b3f46;
      padding: 20px;
      margin: 30px auto;
      width: 80%;
      border-left: 8px solid #61dafb;
      border-radius: 10px;
    }

    .edit {
      font-size: 36px;
      color: #ff6f61;
      background-color: #1e1e1e;
      padding: 20px;
      margin-top: 30px;
      text-align: center;
      border-radius: 10px;
    }

    .edit img {
      width: 200px;
      border-radius: 10px;
      margin: 20px 0 10px 0;
    }

    .name {
      font-size: 30px;
      color: #ffffff;
      font-style: italic;
      margin-top: 10px;
    }

  </style>
</head>
<body>

  <h1>Expert Insight</h1>
  <hr>
  
  <p>Responsive Web Design with HTML5 and CSS</p>
  
  <div class="direct">
    Develop future-proof responsive websites using the latest HTML and CSS techniques.
  </div>

  <div class="edit">
    Third Edition
    <br>
    <img src="photo.jpg" alt="Author's photo">
    <div class="name">
      P.RAJA
    </div>
    <hr>
  </div>

</body>
</html>

```
# OUTPUT:
![alt text](<web/bookapp/static/Screenshot 2025-04-25 142152.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
