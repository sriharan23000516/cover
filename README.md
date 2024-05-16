# Ex.06 Book Front Cover Page Design
## Date:

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
HTML:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Ben Frain</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```

CSS:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Ben Frain</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```

## OUTPUT:
![book-cover](https://github.com/Ravi-1105/cover/assets/139841688/060f7ce9-17eb-4aad-86d4-d51040f4151e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
