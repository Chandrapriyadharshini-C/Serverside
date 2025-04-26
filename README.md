# Ex.05 Design a Website for Server Side Processing
## Date: 23/04/2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

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
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>SURFACE AREA OF RIGHT CYLINDER</title>
<h1 align="center"><font color="red">CHANDRAPRIYADHARSHINI C</font></h1>
<h2 align="center"><font color="red">212223240019</font></h2>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background-color: lightgreen;
}
.edge {
    width: 100%; /* Set width to 100% */
    display: flex;
    justify-content: center; /* Center the content horizontally */
    align-items: center; /* Center the content vertically */
    height: 100vh; /* Set height to 100% of the viewport height */
}
.box {
    border: Thick dashed deeppink;
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: skyblue;
    padding: 20px; /* Add padding for better appearance */
}
.formelt {
    color: black;
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
}
h1 {
    color: black;
    text-align: center;
    padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>SURFACE AREA OF RIGHT CYLINDER </h1>
        <form method="POST">
            {% csrf_token %}
            <div class="formelt">
                Radius : <input type="text" name="Radius" value="{{ r }}"></input>(in m)<br/>
            </div>
            <div class="formelt">
                Height : <input type="text" name="height" value="{{ h }}"></input>(in m)<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"></input><br/>
            </div>
            <div class="formelt">
                Area : <input type="text" name="area" value="{{ area }}"></input>m<sup>2</sup><br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>
```

## SERVER SIDE PROCESSING:
![Screenshot 2025-04-23 110119](https://github.com/user-attachments/assets/359c6868-1707-40eb-9443-813acca2e923)


## HOMEPAGE:
![Screenshot 2025-04-23 111015](https://github.com/user-attachments/assets/df7db4c2-e745-4076-acb0-76a297e53772)


## RESULT:
The program for performing server side processing is completed successfully.
