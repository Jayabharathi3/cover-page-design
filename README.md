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
            top:130px;
            
            font-family:'ink free';
            font-size: large;
        }
        .booktitle{
            font-family: 'gabriola', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 19px;
            color:purple;
        
        }
        
        
        .publisher{
            font-size: medium;
            position: relative;
            color:thistle;
            top:105px;
            left:330px;
        }
        .edition{
            color:yellow;
            font-size: large;
            font-family: 'ink free';
            text-align: right;
            position:relative;
            top:25px;

        }
        .subtitle{
            font-family:'Segoe script';
            font-size: large;
            text-align: center;
            position: relative;
            top:17px;
        }
        .photo{
            position: relative;
            top: 65px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        .text-container {
            position: absolute;
            top: 395px;
            left: 550px; 
            color:black;
            font-size: x-large;
            font-family: 'cambria math',sans-serif ;
        }

         .text-containers {
            position: absolute;
            top: 435px;
            left: 590px; 
            color:black;
            font-size: x-large;
            font-family: 'cambria math',sans-serif;
        }

        .text-containerss {
            position: absolute;
            top: 470px;
            left: 635px; 
            color:black;
            font-size: x-large;
            font-family:  'cambria math',sans-serif;
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
                TiNy  chAnGEs
            </div>

            <div class="subtitle">
                ReMarKAblE  rEsulTs....
            </div>    

            <div class="booktitle">
                <h1>ATOMIC HABITS </h1>
            </div>

            <div class="subtitle">
                An EasY wAy AnD pROvEn WAys TO BuIld gOoD haBIts & bReAk baD ONes
            </div>
            

            <div class="photo">
                <img src="/static/images/author 2.png" width="130" height="145" alt="">
            </div>
            
            <div class="text-container">
               <p>HaBits </p> 
            </div>

            <div class="text-containers">
               <p> deFiNEs </p> 
            </div>

            <div class="text-containerss">
               <p> yOu....</p> 
            </div>

            <div class="author">
               <p><b>Cover page by </b></p>
            </div>
            
            <div class="author">
               <p><b>JAYABHARATHI</b></p>
            </div>

            <div class="publisher">
                Packt>
            </div>
            
            <div class="edition">
                <b>JAMES CLEAR's</b>
            </div>
            
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
            


```

## Output:

## CLIENT OUTPUT:

![bookc1](https://github.com/Jayabharathi3/cover-page-design/assets/120367796/1b165118-3a57-40b6-a352-b84c84206f47)


## SERVER OUTPUT:

![server1](https://github.com/Jayabharathi3/cover-page-design/assets/120367796/daebeb7e-a2e2-4fef-821f-6f8f2c7203d2)



## Result:

The program for designing book cover page using HTML and CSS is executed successfully



