# Ex08 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="rectangle"></div>
      <div class="text-wrapper">Tech Day Events</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <div class="div">Hackathon</div>
      <div class="text-wrapper-2">Quiz</div>
      <div class="text-wrapper-3">Debate</div>
      <div class="text-wrapper-4">Adventures</div>
      <div class="text-wrapper-5">Ideathon</div>
      <img class="r" src="img/r-1.png" />
      <img class="w" src="img/w-1.png" />
      <img class="g" src="img/g-1.png" />
    </div>
  </body>
</html>

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


.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 625px;
  min-height: 956px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 39px;
  left: 39px;
  width: 544px;
  height: 94px;
  background-color: #fa0f0f;
}

.iphone .text-wrapper {
  position: absolute;
  top: 57px;
  left: 125px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .star {
  position: absolute;
  top: 187px;
  left: 98px;
  width: 38px;
  height: 29px;
}

.iphone .img {
  position: absolute;
  top: 269px;
  left: 104px;
  width: 32px;
  height: 29px;
}

.iphone .star-2 {
  position: absolute;
  top: 351px;
  left: 103px;
  width: 34px;
  height: 31px;
}

.iphone .star-3 {
  position: absolute;
  top: 436px;
  left: 102px;
  width: 35px;
  height: 30px;
}

.iphone .star-4 {
  position: absolute;
  top: 519px;
  left: 106px;
  width: 38px;
  height: 33px;
}

.iphone .div {
  position: absolute;
  top: 173px;
  left: 149px;
  width: 349px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 255px;
  left: 145px;
  width: 279px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 341px;
  left: 145px;
  width: 322px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 423px;
  left: 149px;
  width: 253px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 507px;
  left: 160px;
  width: 297px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .r {
  position: absolute;
  top: 623px;
  left: 0;
  width: 339px;
  height: 266px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone .w {
  position: absolute;
  top: 270px;
  left: 446px;
  width: 167px;
  height: 152px;
  aspect-ratio: 1.25;
  object-fit: cover;
}

.iphone .g {
  position: absolute;
  top: 662px;
  left: 352px;
  width: 244px;
  height: 244px;
  aspect-ratio: 1;
  object-fit: cover;
}

```
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="logo" src="img/logo-1.png" />
      <img class="element" src="img/1741092488phpyslgcv-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Tech-day event</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Register</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Login</div>
      <img class="laptop" src="img/laptop-1.png" />
      <img class="robot" src="img/robot-1.png" />
    </div>
  </body>
</html>


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


.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 581px;
  min-height: 956px;
  position: relative;
}

.iphone .logo {
  position: absolute;
  top: 17px;
  left: 47px;
  width: 456px;
  height: 94px;
  aspect-ratio: 4.85;
}

.iphone .element {
  position: absolute;
  top: 111px;
  left: 131px;
  width: 320px;
  height: 313px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 424px;
  left: 27px;
  width: 528px;
  height: 87px;
  background-color: #120c0c;
  border-radius: 10px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 432px;
  left: 100px;
  width: 446px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 54px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 548px;
  left: 153px;
  width: 244px;
  height: 50px;
  background-color: #390dff;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 556px;
  left: 218px;
  width: 179px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 623px;
  left: 153px;
  width: 244px;
  height: 45px;
  background-color: #210af0;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 623px;
  left: 236px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .laptop {
  position: absolute;
  top: 716px;
  left: 291px;
  width: 217px;
  height: 193px;
  aspect-ratio: 1.12;
  object-fit: cover;
}

.iphone .robot {
  position: absolute;
  top: 596px;
  left: 0;
  width: 298px;
  height: 313px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

```
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="rectangle"></div>
      <div class="text-wrapper">Registration Form</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <img class="aw" src="img/aw-1.png" />
      <div class="text-wrapper-3">Phone No.</div>
      <div class="text-wrapper-4">Email Address</div>
      <div class="text-wrapper-5">Dept</div>
      <div class="text-wrapper-6">Events reg.</div>
      <div class="text-wrapper-7">Submit</div>
    </div>
  </body>
</html>


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


.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 526px;
  min-height: 956px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 33px;
  left: 31px;
  width: 463px;
  height: 76px;
  background-color: #0cfd28;
}

.frame .text-wrapper {
  position: absolute;
  top: 42px;
  left: 66px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #131111;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 138px;
  left: 48px;
  width: 431px;
  height: 69px;
  background-color: #d9d9d9;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 146px;
  left: 86px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 235px;
  left: 58px;
  width: 421px;
  height: 75px;
  background-color: #d9d9d9;
}

.frame .rectangle-3 {
  position: absolute;
  top: 346px;
  left: 58px;
  width: 421px;
  height: 78px;
  background-color: #d9d9d9;
}

.frame .rectangle-4 {
  position: absolute;
  top: 460px;
  left: 58px;
  width: 436px;
  height: 76px;
  background-color: #d9d9d9;
}

.frame .rectangle-5 {
  position: absolute;
  top: 575px;
  left: 68px;
  width: 411px;
  height: 65px;
  background-color: #d9d9d9;
}

.frame .rectangle-6 {
  position: absolute;
  top: 671px;
  left: 179px;
  width: 179px;
  height: 42px;
  background-color: #ff0606;
}

.frame .aw {
  position: absolute;
  top: 726px;
  left: 138px;
  width: 290px;
  height: 211px;
  aspect-ratio: 1.37;
  object-fit: cover;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 245px;
  left: 86px;
  width: 373px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 363px;
  left: 77px;
  width: 449px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 468px;
  left: 86px;
  width: 410px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 579px;
  left: 96px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 677px;
  left: 220px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

```


## OUTPUT:
![alt text](<arun/designapp/migrations/Screenshot 2025-12-24 183402.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
