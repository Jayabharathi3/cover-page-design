# Cover-Page-Design

## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

 ## Step 1:

Create a new Django project .

## Step 2:

Create a static file directory and mention the changes in settings.

## Step 3:

Make a new folder named html in static and create a file cover.html in html folder.

## Step 4:

Write down the code for book cover using HTML and CSS.

## Step 5:

Add images and other contents using CSS record a screenshot of it.


## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/bookcover.png);
            background-size: cover;
        }
            

        .toptext{
            color:thistle;

        }

        
        .tophr{
            width:140px;
        }
        
        .author{
            color: white;
            display: inline;
            position: relative;
            text-align: left;
            color:yellow;
            top:150px;
            
            font-family:'ink free';
            font-size: large;
        }
        
        .booktitle{
            font-family: 'gabriola', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            color:purple;
            top: 19px;
        
        }
        
        .publisher{
            font-size: large;
            position: relative;
            top:155px;
            left:330px;
        }
        
        .edition{
            color:yellow;
            font-size: large;
            font-family: ink free;
            position:relative;
            text-align: right;
            top:65px;

        }
        
        .subtitle{
            font-family: 'Segoe script';
            font-size: large;
            text-align: center;
            position: relative;
            top:17px;
        }

        .photo{
            position: relative;
            top: 90px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }

        .text-container {
             position: absolute;
             top: 320px;
             left: 50px; 
             color: black;
             font-size: x-large;
             font-family: 'franklin gothic', sans-serif; 
        }
        
        .text-containers {
             position: absolute;
             top: 360px;
             left: 80px; 
             color: black;
             font-size: x-large;
             font-family: 'franklin gothic', sans-serif; 
        }
        
        .text-containerss {
             position: absolute;
             top: 400px;
             left: 115px; 
             color: black;
             font-size: x-large;
             font-family: 'franklin gothic', sans-serif; 
        }

        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            
            <div class="tophr">
                <hr style="color: red;">
            </div>
            
            <div class="subtitle">
                TiNy chAnGes 
            </div>
            
            <div class="subtitle">
                ReMArkAbLe  rEsULtS ...
            </div>
            
            <div class="booktitle">
                <h1>ATOMIC HABITS</h1>
            </div>
                
            <div class="subtitle">
                An eASy AnD pROveN WAyS tO BUilD GooD haBItS & bREaK BAd ONeS
            </div>  
            
            <div class="photo">
                <img src="/static/images/author 2.png" width="130" height="145" alt="">
            </div>
            
            <div class="text-container">
                <p> HabItS </p>
            </div>
            
            <div class="text-containers">
                <p> dETerMiNeS </p> 
            </div>
            
            <div class="text-containerss">
                <p> yOu... </p>                  
            </div>

            <div class="author">
               <p><b>JaYAbHaRAtHi</b></p>
            </div>
            
            <div class="publisher">
                Avery>
            </div>
            
            <div class="edition">
                <b>First Edition</b>
            </div>
            
            <div class="edition">
                <b>October 2018</b>
            </div>
            
        </div>
    </body>
</html>

```

## Output:

## CLIENT OUTPUT:

![cover](https://github.com/Jayabharathi3/cover-page-design/assets/120367796/02f24e8a-16e1-40da-a64c-18df12cee3ed)


## SERVER OUTPUT:

![image](https://github.com/Jayabharathi3/cover-page-design/assets/120367796/30b394ae-5c27-4871-9212-f613f2dc74dc)


## Result:

The program for designing book cover page using HTML and CSS is executed successfully



