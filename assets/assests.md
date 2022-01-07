1.landing page
2.home page
3.about us
3.register
4.participating countries
5.speakers
6.venue
7.schedule
8.our sponsors
9.contact us






#### ROUGH ####

<!--
<div class="container">
    <a href="" class="nav-link">
        <h3 class="navbar">Home</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">About Us</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">Our Sponsors</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">Speakers</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">Schedule</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">Register Now</h3>
    </a>
    <a href="" class="nav-link">
        <h3 class="navbar">Contact Us</h3>
    </a>

</div>
    <div class="background">
        <br>
        

        <button class="button" style="vertical-align:middle"><span>Let's Start </span></button>
    </div>
<div class="second-div">
    -->

    



.header-basic {
	background-color:black;
	box-shadow: 1px 2px 2px rgba(0, 0, 0, 0.15);
	padding: 20px 40px;
	height: 80px;
	box-sizing: border-box;
}

.header-basic .header-limiter {
	max-width: 1200px;
	text-align: center;
	margin: 0 auto;
}
.header-basic .header-limiter h1 {
	float: left;
	font: normal 28px;
	font-family: 'Raleway', sans-serif;
	line-height: 40px;
	margin: 0;
}

.header-basic .header-limiter h1 span {
	color: #5383d3;
}
.header-basic .header-limiter a {
	color: #ffffff;
	text-decoration: none;
}

.header-basic .header-limiter nav{
	font:24px,'Raleway', sans-serif;;
	line-height: 40px;
	float: center;
    
}
.margin{
    margin-left:40px;
}
.header-basic .header-limiter nav a{
	display: inline-block;
	padding: 0 5px;
	text-decoration:none;
	color: #ffffff;
	font-size: 22px;
	opacity: 0.9;
}

.header-basic .header-limiter nav a:hover{
	opacity: 1;
}

.header-basic .header-limiter nav a.selected {
	color: #608bd2;
	pointer-events: none;
	opacity: 1;
}
@media all and (max-width: 600px) {

	.header-basic {
		padding: 20px 0;
		height: 75px;
	}

	.header-basic .header-limiter h1 {
		float: none;
		margin: -8px 0 10px;
		text-align: center;
		font-size: 24px;
		line-height: 1;
	}

	.header-basic .header-limiter nav {
		line-height: 1;
		float:none;
	}

	.header-basic .header-limiter nav a {
		font-size: 13px;
	}

}
body {
	margin:0;
	padding:0;
}
.pop{
	width: 40px;
	height: 40px;
	margin-left: -100px;
		
}
.icons{float: right;
	
}




    <header class="header-basic">

        <div class="header-limiter">
            <nav>
                <a class="margin" href="homepage.html">Home</a>

                <a class="margin" href="speaker.html">About Us</a>
                <a class="margin" href="speaker.html">Our Sponsers</a>
                <a class="margin" href="speaker.html">Speakers</a>

                <a class="margin" href="schedule.html">Schedule</a>
                <a class="margin" href="https://forms.gle/2eaotVCqkQVGTuHn8" target="_blank"
                    style="color:#5383d3;">Register Now</a>
                <a class="margin" href="venue.html">Contact Us</a>

            </nav>
        </div>
        -->


        
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}

a {
 text-decoration: none;
}
li {
 list-style: none;
}
/* NAVBAR STYLING STARTS */
.navbar {
 display: flex;
 align-items: center;
 justify-content: space-between;
 padding: 20px;
 background-color: teal;
 color: #fff;
 font-family: 'Raleway', sans-serif;
}
.nav-links a {
 color: #fff;
}
/* LOGO */
.logo {
 font-size: 32px;
}
/* NAVBAR MENU */
.menu {
 display: flex;
 gap: 1em;
 font-size: 18px;
}
.menu li:hover {
 background-color: #4c9e9e;
 border-radius: 5px;
 transition: 0.3s ease;
}
.menu li {
 padding: 5px 14px;
}
/* DROPDOWN MENU */
.services {
 position: relative; 
}
.dropdown {
 background-color: rgb(1, 139, 139);
 padding: 1em 0;
 position: absolute; /*WITH RESPECT TO PARENT*/
 display: none;
 border-radius: 8px;
 top: 35px;
}
.dropdown li + li {
 margin-top: 10px;
}
.dropdown li {
 padding: 0.5em 1em;
 width: 8em;
 text-align: center;
}
.dropdown li:hover {
 background-color: #4c9e9e;
}
.services:hover .dropdown {
 display: block;
}
/*RESPONSIVE NAVBAR MENU STARTS*/
/* CHECKBOX HACK */
input[type=checkbox]{
 display: none;
} 
/*HAMBURGER MENU*/
.hamburger {
 display: none;
 font-size: 24px;
 user-select: none;
}
/* APPLYING MEDIA QUERIES */
@media (max-width: 768px) {
.menu { 
 display:none;
 position: absolute;
 background-color:teal;
 right: 0;
 left: 0;
 text-align: center;
 padding: 16px 0;
}
.menu li:hover {
 display: inline-block;
 background-color:#4c9e9e;
 transition: 0.3s ease;
}
.menu li + li {
 margin-top: 12px;
}
input[type=checkbox]:checked ~ .menu{
 display: block;
}
.hamburger {
 display: block;
}
.dropdown {
 left: 50%;
 top: 30px;
 transform: translateX(35%);
}
.dropdown li:hover {
 background-color: #4c9e9e;
}
}





/*
.background {
  height: 100vh;
  width: 100%;
  background-image: url("../assets/1641551225604.jpg");
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
  background-repeat: no-repeat;
}
.container {
  position: sticky;
  margin-top: -20px;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 50px;
  align-items: center;
  font-family: "Raleway", sans-serif;
}

.nav-link {
  text-decoration: none;
  color: white;
  font-size: larger;
}

.nav-link:hover {
  text-shadow: 3px 3px 5px #11aac5;
}

.button {
  font-weight: 500;
  font-family: "Raleway", sans-serif;
  position: absolute;
  bottom: 200px;
  left: 200px;
  display: inline-block;
  border-radius: 15px;
  background-color: #ffffff;
  border: none;
  color: #1a1717;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: "\00bb";
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}

.second-div {
  width: 98vw;
  height: 70vh;
}
*/