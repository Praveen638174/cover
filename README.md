# Ex.06 Book Front Cover Page Design
## Date: 10/05/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Arora's Journey - Book Cover</title>
  <style>
    body {
      margin: 0;
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Segoe UI', sans-serif;
    }

    .book-cover {
      width: 320px;
      height: 480px;
      background: #111;
      color: white;
      position: relative;
      border: 2px solid #fff;
      overflow: hidden;
      box-shadow: 0 0 25px rgba(255, 255, 255, 0.2);
      transition: transform 0.4s, box-shadow 0.4s;
    }

    .book-cover:hover {
      transform: scale(1.05);
      box-shadow: 0 0 50px rgba(255, 255, 255, 0.3);
    }

    .cover-photo {
      width: 100%;
      height: 70%;
      background-image: url('123.jpg');
      background-size: cover;
      background-position: center;
      filter: grayscale(100%) contrast(1.1);
      transition: filter 0.4s ease;
    }

    .book-cover:hover .cover-photo {
      filter: grayscale(50%) brightness(1.1);
    }

    .info {
      padding: 15px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: center;
    }

    .title {
      font-size: 1.8em;
      font-weight: bold;
      letter-spacing: 1px;
      margin-bottom: 10px;
    }

    .author {
      font-size: 1em;
      font-style: italic;
      opacity: 0.8;
      margin-bottom: 10px;
    }

    .edition {
      font-size: 0.9em;
      margin-bottom: 5px;
      opacity: 0.6;
    }

    .publisher {
      font-size: 0.85em;
      opacity: 0.5;
    }

    .border-lines {
      position: absolute;
      top: 8px;
      left: 8px;
      right: 8px;
      bottom: 8px;
      border: 1px dashed rgba(255, 255, 255, 0.1);
      pointer-events: none;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="cover-photo"></div>
    <div class="info">
      <div class="title">THE ONE PRINCE</div>
      <div class="author">by Praveen Raj G</div>
      <div class="edition">Special Edition</div>
      <div class="publisher">A fairytale publication</div>
    </div>
    <div class="border-lines"></div>
  </div>
</body>
</html>



## OUTPUT:

![Alt text](Screenshot234543232.jpeg)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
