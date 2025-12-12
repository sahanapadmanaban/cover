# Ex.05 Book Cover Page Design
## Date:

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html

<html>
    <head>
        <title>CoverPage</title>
        <link rel="stylesheet" type="text/css" href="coverapp.css">

    </head>
    <body>
      
        <div class="container">
            <h1>About the book</h1>
            <hr>
            <p>
                This book provides a comprehensive overview of "Ethical hacking". It is the legal and professional practice of testing computer systems, networks, and applications. This is done to find and fix security weaknesses before malicious hackers can exploit them. It involves using hacking techniques, but with permission and a positive goal. The aim is to protect digital assets and improve overall cybersecurity.
             </p>   
        <div class="quote">
            <p>"A successful hacking methodology is built on accumulated experience with diverse techniques, explored creatively."</p>

        </div>
        <div class="author">
            <h3>P.SAHANA</h3>
            <img src="sahana photo.jpeg" alt="Author Photo" width="150" height="150">
            <p class="text">P.Sahana is a well known writer,singer,artist.She is doing her UG in Saveetha Engineering Colleage.She is interested in writing book about computer science.</p>
        </div>
        <div class="footer">
            <text>SEC PUBLISHERS</text>
            <text>Price: 599rs</text>  
        </div>
        </div>
    </body>
</html>




coverapp.css

body {
   
    
    font-family: Arial, sans-serif;
}
p{
    color:aliceblue;
}
.container {
    
    background-image: url("background cover.png");
     background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    width: 30%;
    margin: 40px auto;
    padding: 20px 40px;
    border-radius: 12px;
    border: 3px;
    height: 700px;
    box-shadow: 0 0 10px black;
}
.text{
    color: black;
    position: relative;
    right: 60px;
}
h3{
    color: aliceblue;
}
h1 {
    color:rgb(97, 201, 192);
}

.quote {
    background: rgb(144, 119, 202);
    border-left: 5px solid rgb(13, 18, 110);
    padding: 10px 20px;
    margin: 20px 0;
    font-style: italic;
    border-radius: 5px;
}

.author {
    display: flex;
    
    background: white;
    padding: 15px;
    border-radius: 10px;
    margin-top: 20px;
    
}

img {
    position: relative;
    right:90px;
    width: 100px;
    height: 130px;
    object-fit: cover;
    margin-right: 15px;
    border-radius: 8px;
}
.footer {
    margin-top: 130px;
    background: #0b3d8a;
    padding: 12px 15px;
    border-radius: 8px;
    color: white;
    display: flex;
    justify-content: space-between;
    font-weight: bold;
}

.price {
    color: yellow;
}

```
## OUTPUT:

![alt text](image.png)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
