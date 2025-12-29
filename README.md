# Ex09 Event Registration Web Application
# Date:20-12-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="SPORTS-DAY-EVENTS">SPORTS&nbsp;&nbsp; DAY&nbsp;&nbsp; EVENTS</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">LOGIN</div>
      <img class="img" src="img/image.svg" />
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">EYES ON THE PRIZE</div>
    </div>
  </body>
</html>



global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}



style.css

.android-medium {
  overflow: hidden;
  background-image: url(./img/android-medium-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 360px;
  min-height: 800px;
  position: relative;
}

.android-medium .SPORTS-DAY-EVENTS {
  position: absolute;
  top: 169px;
  left: 25px;
  width: 320px;
  font-family: "Alfa Slab One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 50px;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 292px;
  left: -101px;
  width: 125px;
  height: 30px;
}

.android-medium .rectangle {
  position: absolute;
  top: 266px;
  left: 86px;
  width: 188px;
  height: 83px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 284px;
  left: 139px;
  width: 93px;
  transform: rotate(-0.3deg);
  font-family: "Alike-Regular", Helvetica;
  font-weight: 400;
  color: #8a05b7;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 50px;
  white-space: nowrap;
}

.android-medium .img {
  position: absolute;
  top: 334px;
  left: -103px;
  width: 135px;
  height: 39px;
}

.android-medium .div {
  position: absolute;
  top: 400px;
  left: 88px;
  width: 180px;
  height: 75px;
  background-color: #ffcc04;
  border: 5px solid;
  border-color: #000000;
  filter: blur(2px);
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 411px;
  left: 120px;
  width: 208px;
  font-family: "Alike-Regular", Helvetica;
  font-weight: 400;
  color: #8a05b7;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 50px;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 745px;
  left: 22px;
  width: 322px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #000000;
  font-family: "Asset-Regular", Helvetica;
  font-weight: 400;
  color: #fdfcfe;
  font-size: 14px;
  letter-spacing: 0;
  line-height: 50px;
  white-space: nowrap;
}
```
# OUTPUT:
<img width="1460" height="779" alt="Screenshot 2025-12-29 130836" src="https://github.com/user-attachments/assets/16a5ec3b-4945-4245-82df-021fb6538bea" />
<img width="1453" height="768" alt="Screenshot 2025-12-29 130855" src="https://github.com/user-attachments/assets/847a5696-d61c-40c6-a41a-f9bf24e7c0aa" />
<img width="1461" height="771" alt="Screenshot 2025-12-29 130912" src="https://github.com/user-attachments/assets/ba664a70-40b3-44a4-bbf9-bb4051167d2f" />
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
