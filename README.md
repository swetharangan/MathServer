# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

'''

<!DOCTYPE html>
<html>
<head>
<title>Surface Area Of Right Cylinder</title>
<style type="text/css">
body
{
    background-color:pink;
}
.edge
{
    width: 1440px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 100px;
}
.box
{
    display:block;
    border: ridge black;
    width: 900px;
    min-height: 500px;
    font-size: 20px;
    background-color:lightblue;
}
.my
{
    color:red;
    text-align: center;
    margin-top: 8px;
    margin-bottom: 9px;
}
.my1
{
    color:red;
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
    box-sizing: 20px;
}
h1
{
    color:black;
    text-align: center;
    padding-top: 20px;
}
</style>
</head>
<body>
    <div class="edge" align="center">
        <div class="box">
            <h1>SURFACE AREA OF A RIGHT CYLINDER</h1>
            <h2> SWETHA.R (212223040221)</h2>
            <br>
            <br>
            <div class="my">
                <b>RADIUS : </b> <input type="text" name="Radius"></input> (in m)<br/>
                <br>
            </div>
            <div class="my">
                <b>HEIGHT : </b> <input type="text" name="Height"></input> (in m)<br/>
                <br>
            </div>
            <div class="my1">
                <input type="button" value="CALCULATE" onclick="calculateArea()"></input><br/>
                <br>
            </div>
            <div class="my">
                <b>AREA : </b> <input type="text" name="area"></input> m<sup>2</sup><br/>
            </div>
        </div>
    </div>
    <script type="text/javascript">
        function calculateArea()
        {
            var radius = parseFloat(document.getElementsByName("Radius")[0].value);
            var height = parseFloat(document.getElementsByName("Height")[0].value);
            var area = 2 * Math.PI * radius * (radius + height);
            document.getElementsByName("area")[0].value = area.toFixed(2);
        }
    </script>
</body>
</html>


'''



## SERVER SIDE PROCESSING:

![Screenshot 2024-05-07 160333](https://github.com/swetharangan/MathServer/assets/163235949/fb854783-42ea-4ae7-9fbb-84f990a967fd)



## HOMEPAGE:

![Screenshot 2024-05-07 155929](https://github.com/swetharangan/MathServer/assets/163235949/c8367cfd-85dc-4afa-ae54-46bfcd1ab959)




## RESULT:
The program for performing server side processing is completed successfully.
