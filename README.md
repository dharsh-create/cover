# Ex.06 Book Front Cover Page Design

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Front Cover Page</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: 'Times New Roman', serif;
    }

    .book-cover {
      width: 600px;
      height: 850px;
      margin: 50px auto;
      background: radial-gradient(circle at top left, #ff6600, #ff3300, #cc0000);
      background-image: repeating-linear-gradient(
        45deg,
        rgba(255, 255, 0, 0.2) 0px,
        rgba(255, 100, 0, 0.15) 10px,
        rgba(255, 0, 0, 0.2) 20px
      );
      border: 10px solid red;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
      padding: 40px;
      box-sizing: border-box;
      position: relative;
      color: white;
      text-align: center;
      background-blend-mode: overlay;
    }

    .book-cover::before {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(180deg, rgba(255,140,0,0.3), rgba(255,0,0,0.5));
      z-index: 0;
    }

    .book-cover * {
      position: relative;
      z-index: 1;
    }

    .top-text {
      position: absolute;
      top: 20px;
      left: 30px;
      font-size: 18px;
      border-bottom: 1px solid white;
      padding-bottom: 5px;
      color: #fff;
    }

    h1 {
      font-size: 34px;
      font-weight: bold;
      margin-top: 120px;
      line-height: 1.4;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.4);
    }

    h3 {
      font-size: 18px;
      margin-top: 30px;
      color: #f8f8f8;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
    }

    .special {
      position: absolute;
      bottom: 100px;
      left: 40px;
      font-size: 20px;
      font-weight: bold;
      color: white;
    }

    .author {
      position: absolute;
      bottom: 60px;
      left: 40px;
      font-size: 18px;
      font-weight: bold;
      color: white;
    }

    .college {
      position: absolute;
      bottom: 60px;
      right: 40px;
      font-size: 18px;
      font-weight: bold;
      color: white;
    }

    .photo {
      position: absolute;
      bottom: 120px;
      right: 50px;
      width: 100px;
      height: 120px;
      border: 2px solid white;
      background-color: #fff;
      overflow: hidden;
    }

    .photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="top-text">SEC Insights</div>

    <h1>FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>

    <h3>Deep Dive in HTML, CSS & JS Basics<br>Top Seller of 2025</h3>

    <div class="special">SPECIAL EDITION</div>
    <div class="author">Dharshini.V</div>
    <div class="college">SEC</div>

    <div class="photo">
      <img src="WhatsApp Image 2025-11-10 at 8.29.20 AM.jpeg" alt="Author Photo">
    </div>
  </div>

</body>
</html>
```


## OUTPUT:
<img width="1919" height="1073" alt="Screenshot 2025-11-10 085618" src="https://github.com/user-attachments/assets/fb8725d6-8811-4aec-9941-161ac6ed9657" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
