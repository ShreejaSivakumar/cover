# Ex.06 Book Front Cover Page Design
## Date:08/10/25

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

<!DOCTYPE html>  <html lang="en">    <head>    
    <meta charset="UTF-8">    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <title>Book Cover</title>    
    <style>    
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');  body {    
        display: flex;    
        justify-content: center;    
        align-items: center;    
        height: 100vh;    
        margin: 0;    
        background-color: #f0f2f5;    
        font-family: 'Roboto', sans-serif;    
    }    .book-cover {    
    width: 350px;    
    height: 500px;    
    position: relative;    
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);    
    border-radius: 8px;    
    overflow: hidden;    
    background: linear-gradient(180deg, #023160 0%, #044998 50%, #0267fe 100%);    
    display: flex;    
    flex-direction: column;    
    justify-content: space-between;    
    padding: 25px;    
    color: #ffffff;    
    border: 3px solid #ffffff;    
}    

.header {    
    display: flex;    
    justify-content: space-between;    
    font-size: 14px;    
    font-weight: 700;    
}    

.title-section {    
    text-align: center;    
    margin-top: 50px;    
}    

.title {    
    font-size: 28px;    
    font-weight: 700;    
    line-height: 1.2;    
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);    
}    

.subtitle {    
    font-size: 16px;    
    font-weight: 400;    
    margin-top: 15px;    
    opacity: 0.9;    
}    

.tagline {    
    font-size: 12px;    
    margin-top: 5px;    
    font-style: italic;    
}    

.author-section {    
    display: flex;    
    align-items: flex-end;    
    justify-content: space-between;    
}    

.author-info {    
    display: flex;    
    align-items: center;    
    gap: 15px;    
}    
    
.author-text {    
    display: flex;    
    flex-direction: column;    
}    

.special-edition {    
    font-size: 10px;    
    text-transform: uppercase;    
    font-weight: 700;    
    letter-spacing: 1px;    
    margin-bottom: 5px;    
}    

.author-name {    
    font-size: 18px;    
    font-weight: 700;    
}    

.author-photo {    
    width: 70px;    
    height: 70px;    
    border-radius: 50%;    
    object-fit: cover;    
    border: 2px solid #ffffff;    
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);    
}

</style>  </head>    
<body>    
    <div class="book-cover">    
        <div class="header">    
            <span>SEC Insights</span>    
            <span>SEC</span>    
        </div>  <div class="title-section">    
        <h1 class="title">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>    
        <p class="subtitle">Deep Dive in HTML, CSS & JS Basics</p>    
        <p class="tagline">Top seller of 2025</p>    
    </div>    <div class="author-section">    
    <div class="author-info"> 
        <img src="shreeja.jpeg" alt="Author Photo" class="author-photo">   
        <div class="author-text">    
            <p class="special-edition">SPECIAL EDITION</p>    
            <p class="author-name">Shreeja</p>    
        </div>    
    </div>
    



## OUTPUT:



![Screenshot_8-10-2025_162653_127 0 0 1](https://github.com/user-attachments/assets/a722350c-4fa1-42c2-ae5e-38239ca8850a)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
