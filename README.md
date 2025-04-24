# Ex.06 Book Front Cover Page Design
## Date:

24-APRIL-2025
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

HTML CODE

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/css2?family=Creepster&family=Nosifer&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>
<style>
h3{
  letter-spacing: 20px;
}
</style>
<body bgcolor="white">
  <br>

    <div class="container">
        <img src="image.png" align="center" height="1000" width="650">
        <div class="text" style="font-family: 'Nosifer', cursive; font-size: 45px; color: red;">
          Before you
        </div>
        <div class="text1" style="font-family: 'Nosifer', cursive; font-size: 100px;">
          sleep
        </div>
      <div class="text2" style="font-family: 'Optima';font-size:8px;">
        <h3>WRITTEN      BY</h3>
      </div>
      <div class="text3" style="font-family: 'Optima';font-size:8px;">
          <h3>S J WATSON</h3>
        
      </div>
      
      
      
    
</body>
</html>

```

CSS CODE

```
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  .container{
    width:100%;
    height: auto;
    position: relative;
  
  }
  .container img{
    display: block;
    margin: auto;
    
  }
  .font-creepster {
      font-family: 'Creepster', cursive; 
    }
    
  .font-nosifer {
      font-family: 'Nosifer', cursive;
    }
  .container .text{
      position: absolute;
      color: rgb(78, 9, 9);
      top: 125px;
      left: 750px;
      margin: auto;
      width: 50%;
      padding: 10px;
      
    }
  
    .container .text1{
      position: absolute;
      color: rgb(146, 8, 8);
      top: 165px;
      left: 725px;
      margin: auto;
      width: 50%;
      padding: 10px;
      
    }
  .container .text2{
    position: absolute;
      color: rgb(146, 8, 8);
      top: 825px;
      left: 815px;
      margin: auto;
      width: 50%;
      padding: 10px;
      letter-spacing: 4px;
  }
  .container .text3{
    position: absolute;
      color: rgb(146, 8, 8);
      top: 850px;
      left: 810px;
      margin: auto;
      width: 50%;
      padding: 10px;
      letter-spacing: 4px;
  }

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/b30e724b-e17c-49b4-bcff-1b26fc21d200)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
