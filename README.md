# Ex:08 Event Registration Web Application
## Date:25/12/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Page 1 html

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
      <img class="image" src="img/image-3.png" />
      <p class="talents-win-games">
        “Talents win games, but teamwork and
        intelligence&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;win champions”
      </p>
      <img class="img" src="img/image-2.png" />
    </div>
  </body>
</html>

page 1 global css


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

page 1 style css


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 636px;
  min-height: 803px;
  display: flex;
  flex-direction: column;
}

.android-medium .image {
  height: 109px;
  margin-top: 189px;
  aspect-ratio: 4.04;
  margin-left: 99px;
  width: 438px;
  object-fit: cover;
}

.android-medium .talents-win-games {
  margin-left: 99px;
  width: 424px;
  height: 155px;
  margin-top: 23px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  height: 286px;
  margin-top: 17px;
  aspect-ratio: 1.53;
  margin-left: 99px;
  width: 438px;
  object-fit: cover;
}

page 2 html

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
      <div class="text-wrapper">Special Games</div>
      <div class="cricket-football">
        Cricket<br />Football<br />Hockey<br />Kho-Kho<br />Badminton<br />Kabbadi<br />Volleyball<br />Throwball
      </div>
      <img class="image" src="img/image-4.png" />
      <img class="img" src="img/image-5.png" />
      <img class="image-2" src="img/image-6.png" />
      <img class="image-3" src="img/image-7.png" />
    </div>
  </body>
</html>

page 2 global css


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

page 2 style css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 805px;
  position: relative;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 39px;
  left: 41px;
  width: 364px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .cricket-football {
  position: absolute;
  top: 144px;
  left: 191px;
  width: 224px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .image {
  top: 63px;
  left: 450px;
  width: 225px;
  height: 225px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.android-medium .img {
  top: 172px;
  left: 0;
  width: 199px;
  height: 232px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.android-medium .image-2 {
  top: 540px;
  left: 83px;
  width: 505px;
  height: 187px;
  aspect-ratio: 2.71;
  position: absolute;
  object-fit: cover;
}

.android-medium .image-3 {
  top: 263px;
  left: 450px;
  width: 225px;
  height: 225px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

page 3 html

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
      <img class="image" src="img/image-8.png" />
      <img class="img" src="img/image-1.png" />
      <img class="image-2" src="img/image-9.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="we-are-all-eagerly">
        “We are all eagerly waiting<br />for your participation in <br />the sports events”
      </p>
    </div>
  </body>
</html>

page 3 global css


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

page 3 style css


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 805px;
  position: relative;
}

.android-medium .image {
  top: 552px;
  left: 76px;
  width: 527px;
  height: 253px;
  aspect-ratio: 2.08;
  position: absolute;
  object-fit: cover;
}

.android-medium .img {
  top: 65px;
  left: 43px;
  width: 614px;
  height: 125px;
  aspect-ratio: 4.92;
  position: absolute;
  object-fit: cover;
}

.android-medium .image-2 {
  top: 220px;
  left: 27px;
  width: 239px;
  height: 124px;
  aspect-ratio: 1.93;
  position: absolute;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 269px;
  left: 405px;
  width: 221px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .we-are-all-eagerly {
  position: absolute;
  top: 391px;
  left: 121px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}


```

##OUTPUT:
<img width="1613" height="906" alt="Screenshot 2025-12-25 114016" src="https://github.com/user-attachments/assets/d418d0d1-702c-440e-bbca-9eaa593704cc" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
