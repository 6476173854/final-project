<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>
* {
  box-sizing: border-box;
}
html{
    background-color:rgb(200, 147, 190);
  color:dark rgb(112, 216, 148);
}
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
 background-color:rgb(155, 216, 190);
  color:dark rgb(41, 118, 63);
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #5c9396;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: rgb(113, 230, 189);

}
.fa {
    padding: 20px;
    font-size: 30px;
    text-decoration: none;
  

    text-align: center;
    text-decoration: none;
    margin: 5px 2px;
  }
  
  .fa:hover {
      opacity: 0.7;
  }
  
  .fa-facebook {
    background: #3B5998;
    color: white;
  }
  
  .fa-twitter {
    background: #55ACEE;
    color: white;
  }
  
  .fa-google {
    background: #dd4b39;
    color: white;
  }
  
  .fa-linkedin {
    background: #007bb5;
    color: white;
  }
  
  .fa-youtube {
    background: #bb0000;
    color: white;
  }
  
  .fa-instagram {
    background: #125688;
    color: white;
  }
  
  .fa-pinterest {
    background: #cb2027;
    color: white;
  }

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: rgb(15, 100, 84);
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: center
  ;
}

/* Change color on hover */
.navbar a:hover {
  background-color:rgb(196, 160, 196);
  color:rgb(130, 38, 217);
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  background-color: #5c9396;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f04a4a;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color:skyblue;
  padding: 20px;
  float:center;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: rgb(128, 222, 208);
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background:rgb(192, 255, 241);
}
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}


</style>
</head>
<body>

<div class="header">
  <h1>Mirchi-Dhaba</h1>
  <p>Variety of food</p>
</div>

<div class="navbar">
  <a href="#" class="menu">MENU</a>
  <a href="#" class="contact">Contact Us</a>
  <a href="#" class="about">About Us</a>
  <a href="#" class="right">Work With Us</a>
</div>

<div class="row">
  <div class="side">
    <h2>About us</h2>
    <h5>WE located in the GTA region </h5>
    <div class="img" style="height:200px;">
            <img src="images/mirchi dhaba.jpg" alt="our branch" width="200" height="200">
    </div>
    <p><b>there are  multipe dishes that we can enjoy everyday you can see some dishes below with picture and menu card</b></p>
    <h3></h3>
    
    <div class="fakeimg" ><img src="images/download (1).jpg" width="200" height="200"></div><br>
    <div class="fakeimg" ><img src="images/download (2).jpg" width="200" height="200"></div><br>
    <div class="fakeimg" ><img src="images/download (3).jpg" width="200" height="200"></div>
    <h3>Contact Form</h3>

<div class="container">
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>
  </div>
 
  <div class="main">
    <h2>MENU</h2>
    <img src="images/download (4).jpg">
    <h5>veg option,best dish of the year, Dec 21, 2019</h5>
    <h2>Another location</h2>
    
  
   <div>
    <img src="images/download.jpg" width="200" height="300">
    <p>we are in scarborough</p>
   </div>
    <p>Shahi Paneer<br>
      Originating from India’s Mughlai cuisine, shahi paneer is a rich, hearty and nutritious cheese.
      <div>
    <h2>new dish</h3>
    <h5>NON-veg option,best dish of the year,Apr 2, 2015</h5>
  
</div>

<div class="links">
  <h2>First location</h2>
    <p><iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d11541.004568527896!2d-79.82908826890868!3d43.68454199503338!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sindian%20restaurants!5e0!3m2!1sen!2sca!4v1701217059770!5m2!1sen!2sca" width="300" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p>
  <h2>Second location</h2><p1><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d23045.377108779063!2d-79.26027981745017!3d43.77966420013753!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89d4d044aa9655c5%3A0xb1cb47734d5a6d7a!2sNew%20Mirchi%20Dhaba!5e0!3m2!1sen!2sca!4v1701816030273!5m2!1sen!2sca" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p1>
  <div class="footer">
    <h2>footer</h2>

    <!-- Add font awesome icons -->
<a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#" class="fa fa-google"></a>
<a href="#" class="fa fa-linkedin"></a>
<a href="#" class="fa fa-youtube"></a>
<a href="#" class="fa fa-instagram"></a>
<a href="#" class="fa fa-pinterest"></a>

</div>
</div>

</body>
</html>
