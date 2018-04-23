## Welcome to Jesse's travel pages

Travel doesn't have to be expensive.  The adventure will be worthwile.  And the world isn't as dangerous as many make it out to be!

### Where I've been

//TODO add a colored in image of places been

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

body {
  background-color: #664433;
  font-family: verdana;
  margin:0;
  padding:0;
  border:0;
}

/*Box Model Example, Outline example*/
header {
  background-color: #abab89;
  color: #000000;
  text-align: center;
  padding: 10px;
  border: 5px solid green;
  margin: 10px;
  margin-left: 220px;
  overflow:auto;
}

nav {
  padding: 0px;
  float: left;
  margin: 0;
  height: 100%;
}

/*Max-width example*/
article {
  background-color: #212121;
  color: #ffffff;
  padding: 20px;
  margin: auto;
  max-width: 600px;
  overflow: auto;
}

.fam ul {
	list-style-type: none;
}

.fam ul li a{
	text-decoration: none;
	color: white;
}

.fam ul li a:hover{
	text-decoration: none;
	color: green;
}

footer {
  float: left;
  background-color: #afafaf;
  text-align: center;
 
  width: 100%;
  clear: left;
}

/*Navigation Bar*/
nav ul {
  list-style-type: none;
  margin:0;
  padding:0;
  border:0;
  width: 200px;
  overflow: hidden;
  position:fixed;
  background-color: #121212;
  height:100%;
}

nav ul li {
  font-size: 15px;
  font-weight:bold;
  text-align:center;  
  border-bottom:1px solid #434343;
}

nav ul li a {
  color:white;
  display:block;
  padding:10px;
  text-decoration:none;
}

nav a:hover {
  background-color: #000000;
  color:white;
  padding:10px;
  text-decoration:none;
}

#toptitle {
  font-family:"Arial Black", Gadget, sans-serif; 
}

#subtitle {
  font-family:"Comic Sans MS", cursive, sans-serif;
}

div.tree {
    position: relative;
    border: 3px solid #73AD21;
	height: 720px;
	width: 956px;
	margin-left: 220px;
	float: left;
}

div.picframe {
    position: absolute;
    width: 150px;
    height: 200px;
    border: 3px solid #73AD21;
	display: block;
}

div.picframe: hover {
	border: 4px solid #eeeeee;
	opacity: 0.7;
}

#grandpa1 {
    left: 80px;
	bottom: 240px; 
    background: url('LloydMare.png') 0 0;
	background-position: -260px -15px; /*x,y*/
	background-size: 500px;
	background-repeat: no-repeat;
}

#grandma1 {
    left: 220px;
	top: 40px; 
    background: url('LloydMare.png') 0 0;
	background-position: -70px -80px; /*x,y*/
	background-size: 500px;
	background-repeat: no-repeat;
}

#grandpa2 {
    right: 250px;
	top: 30px; 
    background: url('Don.jpg') 0 0;
	background-position: 0px -10px;
	background-size: 150px;
	background-repeat: no-repeat;
}
#grandma2 {
    right: 70px;
	bottom: 280px; 
    background: url('Bonnie.png') 0 0;
	background-position: 0px -10px;
	background-size: 150px;
	background-repeat: no-repeat;
}

#dad1 {
    left: 290px;
	bottom: 220px; 
    background: url('scott.png') 0 0;
	background-position: 0px 0px;
	background-size: 160px;
	background-repeat: no-repeat;
}

#mom2 {
    right: 300px;
	bottom: 240px; 
    background: url('Liz.jpg') 0 0;
	background-position: 0px -20px;
	background-size: 150px;
	background-repeat: no-repeat;
}

#me {
    right: 350px;
	bottom: 10px; 
    background: url('Jacob.jpg') 0 0;
	background-position: -20px 0px;
	background-size: 200px;
	background-repeat: no-repeat;
}

.profpic {
	width: 240px;
	float: left;
	border: 4px solid black;
	margin: 20px;
}

div.desc {
	position: absolute;
	top:167px;
	left:0px;
	font-size: 20px;
    padding: 5px;
	visibility:hidden;
    text-align: center;
	width: 140px;
	color:black;
	background-color: #fbfbfb;
}

div.picframe:hover .desc{

	visibility: visible;
}
