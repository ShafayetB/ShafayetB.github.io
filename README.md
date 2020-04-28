<!DOCTYPE html>
<!-- saved from url=(0026)https://shafayetb.github.io/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <title>Shafayet Bhuiyan</title>
  <style>
  
  
/* Utils */

.clear {
	clear: both;
}
.purple {
	color: #837c9a;
}

.block {
	margin: 25px 30px;
}
	.block h1 {
		margin-left: -5px;
		font-weight: 200;
	}

.last.block {
	margin-bottom: 110px;
}

.horizontal_list {
	margin: 0;
	padding: 0;
	list-style-type: none;
}
	.horizontal_list li {
		float: left;
	}
	.horizontal_list li:before {
		content: none;
	}
	.horizontal_list li { 
		padding-left: 0; 
		text-indent: 0;
	}

.list-horizontal li {
	display:inline-block;
}
.list-horizontal li:before {
	content: '\00a0\2022\00a0\00a0';
	/* color:#999; */
	color:rgba(83, 183, 201, 0.5);
	font-size:14px;
}
.list-horizontal li:first-child:before {
	content: '';
}

.horizontal_line{
	margin: 34px 0 0 30px;
	height: 26px;
	position: relative;	
}
	.line_left,
	.line_right{
		border-top: 1px solid #434247;
		width: 305px;
		margin-top: 13px;
	}
	.line_left{
		float: left;
	}
	.line_right {
		float: right;
	}
	.left_circle, 
	.central_circle, 
	.right_circle {
		background: rgb(69,68,73);
		background: rgba(255,255,255, 0.15);
		position: absolute;
		border-radius: 50px;
	}
	.left_circle, 
	.right_circle {
		width: 13px;
		height: 13px;
		top: 7px;
	}
	.left_circle{
		left: 314px;
	}
	.central_circle{
		width: 26px;
		height: 26px;		
		top: 0px;
		left: 322px;
	}
	.right_circle{
		left: 343px;
	}
	
/* Main tags */

body {
	background: url(http://subtlepatterns2015.subtlepatterns.netdna-cdn.com/patterns/dark_wall.png) repeat;
	margin: 0;
}

h1,h2,h3, h4 {
	font-family: 'Lato', Helvetica, sans-serif;
	font-weight: 300;
	color: rgb(247, 239, 239);
}
	h1 {
		font-size: 48px;
		font-weight: 300;
		margin: 20px 0;
	}
	h2 {
		font-size: 28px;
		margin: 32px 0 24px;
	}
	h3 {
		font-size: 24px;
	}
	h4 {
		font-size: 18px;
		font-weight: 400;
	}

blockquote {
	font-style: italic;
	margin: 25px 0;
	padding-left: 20px;
	border-left: 2px solid rgb(214, 223, 218);
}
	
blockquote, p , a, li {
	font-family: 'Lato', Helvetica, sans-serif;
	font-weight: 300;
	font-size: 15px;
	color: rgb(250, 250, 250);
}

a:focus { 
    outline: none;
}

ul {
    list-style: none;
    padding:0;
    margin:0;
}
	li { 
		padding-left: 1em; 
		text-indent: -.7em;
	}
	li:before {
		content: "• ";
		color: #c5c2d1;;
		font-size: 20px;
		padding-right: 8px;
	}
/* Containers size */

#main_container {
	width: 960px;
	height: 100%;
	margin: 0 auto;
}
	#header {
		height: 130px;
		border-bottom: 1px solid #403F44;
	}
		.header_logotype_container {
			width: 260px;
			height: 130px;
			border-right: 1px solid #403F44;
			float: left;
		}
		.header_menu_container {
			height: 130px;
			width: 699px;
			float: left;
		}
			.header_menu_container a {
				font-family: 'Lato', Helvetica, sans-serif;
			}
	#left_col {
		width: 260px;
		float: left;
	}
	#content_container {
		width: 699px;
		height: 100%;
		border-left: 1px solid #403F44;
		float: left;
	}
	#footer {
		width: 960px;
		height: 60px;
		border-top: 1px solid #403F44;
		display: inline-block;
	}

/* HEADER */

.logotype_name{
	text-transform: uppercase;
	font-size: 32px;
	margin: 43px 0 0;
}
.logotype_occupation{
	text-transform: uppercase;
	margin-top: 5px;
	color: #9ac2b3;
	font-size: 14px;
	letter-spacing: 2px;
	padding-left: 7px;
}

.download_print_buttons {
	width: 225px;
	height: 45px;
	float: right;
}
	.download_print_buttons a {
		text-decoration: none;
		font-size: 12px;
		font-family: 'Lato', Helvetica, sans-serif;
		font-style: italic;
		line-height: 45px;
		padding: 16px 17px;
		background: #353638;
	}
		.download_print_buttons a:hover {
			background: #020609;
		}
		.download_print_buttons .icon {
			color: #02070a;
			padding-right: 6px;
			font-style: normal;
			font-size: 18px;
		}
		.icon-angle-double-right {
			position: relative;
			top: 2px;
		}
			.download_print_buttons a:hover .icon {
				color: #e4e3e8;
			}
			
.header_menu {
	width: 699px;
	margin-top: 40px;
	margin-left: 5px;
}
	.header_menu a{
		text-decoration: none;
		padding: 0 20px;
		border-left: 1px solid #e4e3e8;
		font-size: 16px;
		font-weight: 400;
	}
	.header_menu a.no_border{
		border-left: none;
	}
		.header_menu a:hover {
			color: #837c9a;
		}
		
/* LEFT NAV */

#left_nav h2 {
	margin: 0;
	font-size: 24px;
}

.profile_frame{
	width: 180px;
	height: 220px;
	background: black;
	border: 1px solid #403F44;
	margin-top: 30px;
}
	.profile_picture{
		width: 210px;
		height: 240px;
		margin:10px;
		background: url(//s3-us-west-2.amazonaws.com/s.cdpn.io/86033/profile/profile-512_3.jpg) 100% /210px no-repeat;
	}

.hello_content,
.contact_details_content {
	margin-top: 25px;
}

.hello_content{
	width: 230px;
}
.contact_details_content h2 + p.purple{
	margin-top: 10px;
}
.contact_details_content p{
	margin: 0;
}
.contact_details_content p.purple{
	margin-top: 25px;
}

.send_message_button,
.special_button {
	margin-top: 25px;
	display: block;
	background: rgb(204, 203, 212);
	width: 230px;
	height: 50px;
	position: relative;
	z-index: 1;
}
	.cut1:after {
		content: "";
		position: absolute;
		bottom: -19px;
		left: -20px;
		width: 30px;
		height: 30px;
		z-index: 9;
		background: url(http://subtlepatterns2015.subtlepatterns.netdna-cdn.com/patterns/dark_wall.png) repeat;
    transform: rotate(45deg);
	}
	.cut2:before {
	    content: "";
	    position: absolute;
	    top: -19px;
	    right: -20px;
	    width: 30px;
	    height: 30px;
	    z-index: 9;
	    background: url(http://subtlepatterns2015.subtlepatterns.netdna-cdn.com/patterns/dark_wall.png) repeat;
      transform: rotate(45deg);
	}
	.content {
	    text-align: center;		
	    color: #04080b;
	    width: 100%;
	    height: 40px;
	    position: absolute;
	    z-index: 2;
	    font: 18px 'Lato', Arial, sans-serif;
	    margin: 0;
	    padding: 16px 0 0;
        top: -4px;
        bottom: 10px;
	    border-top: 1px solid #403F44;
	    border-bottom: 1px solid #403F44;
	}
	.send_message_button:hover,
	.special_button:hover {
		background: #29C782;
	}

.get_social_content {
	margin-top: 15px;
}
  .get_social_content h2{
    margin-bottom: 8px;
  }
	.social_icons {
		margin-left: -8px;
	}
	.social_icons a {
		font-size: 35px;
		text-decoration: none;
		color: #000507;
		padding: 0;
		padding: 0 5px;
	}
		.social_icons a span.invisible {
			display:none;
		}
		.social_icons .facebook:hover{
			background: #3b5998;
			color: #dfe3ee;
			border-top-right-radius: 50px;
			border-bottom-left-radius: 50px;
		}
		.social_icons .github:hover{
			background: rgb(126, 151, 160);
			color: #fff;
			border-top-left-radius: 50px;
			border-bottom-right-radius: 50px;
		}
		.social_icons .linkedin:hover{
			background: #007bb6;
			color: #fff;
			border-top-right-radius: 50px;
			border-bottom-left-radius: 50px;
		}

.footer_name {
	font-style: italic;
	margin-top: 20px;
}

/* Profile Content */

.profile_quote {
	position: relative;
	/* margin-left: 5px; */
}
	.profile_quote p {
		font-size: 17px;
		width: 455px;
	}
	.profile_quote  .entypo-quote {
		color: #3d3a41;
		font-size: 80px;
    font-style: normal;
		position: absolute;
		top: -20px;
		right: 70px;
		cursor: default;
	}

.philosophy_content {
	margin-top: 20px;
}
	.philosophy_content p {
		margin: 0;
		width: 370px;
		float: left;
	}
	.philosophy_content ul {
		float: left;
		padding-left: 40px;
	}

.slide-left {
	/* padding-left: 5%; */
	line-height: 20%;
	position: relative;
}
.award{
	line-height: 120%;
}

  
  
  </style>


</head>

<body>
  
<!-- MAIN CONTAINER -->
		<div id="main_container">
      <!-- HEADER -->
      <div id="header">
        <!-- LOGOTYPE/NAME -->
        <div class="header_logotype_container">
          <h1 class="logotype_name">Md. Shafayet <span class="purple">Bhuiyan</span></h1>
        </div>
        <!-- MAIN MENU -->
        <div class="header_menu_container">
          <!-- <ul class="download_print_buttons horizontal_list">
            <li><a href="#"><span class="icon entypo-download"></span>Download CV</a></li>
            <li><a href="#"><span class="icon entypo-print"></span>Print CV</a></li>
          </ul> -->
          <div class="clear"></div>
          <ul class="header_menu horizontal_list">
            <li><a class="no_border purple" href="https://sites.google.com/view/shafayetbhuiyan/home#">Education</a></li>
            <li><a href="https://sites.google.com/view/shafayetbhuiyan/home#skills">Skills</a></li>
          
            <li><a href="https://sites.google.com/view/shafayetbhuiyan/home#awards">Awards</a></li>
          </ul>
        </div>
      </div>
      <!-- LEFT COL -->
      <div id="left_col">
        <div class="profile_frame">
          <!-- <div class="profile_picture"></div> -->
        </div>
        <div class="hello_content">
          <h2>Hello!</h2>
          <p>I'm passionate about technology and human behavior, hardworker and a fast-learner.</p>
        </div>
        <div class="contact_details_content">
          <h2>Contact details</h2>
          <p class="purple">Phone:</p>
          <p>+8801715131849</p>
          <p class="purple">Email:</p>
          <p>shafayet.cse@gmail.com</p>		  <!--
          <p class="purple">Adress:</p>
          <p>Mahakhali</p>
          <p>Dhaka, Bangladesh</p>
          <p>1212</p> -->
        </div>
        <a href="mailto:shafayet.cse@outlook.com" class="send_message_button">
          <span class="cut1"></span>
          <span class="cut2"></span>
          <span class="content">Send me a message <span class="fontawesome-double-angle-right"></span></span>
        </a>
        <!--<div class="get_social_content">
          <h2>Get social</h2>
          <ul class="social_icons horizontal_list">
            <li><a class="facebook" href="https://www.facebook.com/sbshafayet"><i class="fab fa-facebook"></i><span class="invisible">Facebook</span></a></li>
            <li><a class="github" href="https://github.com/ShafayetB"><i class="fab fa-github"></i><span class="invisible">Twitter</span></a></li>
            <li><a class="linkedin" href="https://www.linkedin.com/in/shafayetbhuiyan/"><i class="fab fa-linkedin"></i><span class="invisible">LinkedIn</span></a></li>
          -->
		  
		  
			<h3 style="color: white;">Get Social</h3>
			 <a href="https://www.facebook.com/sbshafayet/" style="color: #0000FF; font-size: 22px;">facebook</a></br>
		  	 <a href="https://www.linkedin.com/in/shafayetbhuiyan/"  style="color:#1E90FF;; font-size: 20px;">LinkIn</a></br>
			<a href="https://www.github.com/ShafayetB" style="color:#DC622C; font-size: 20px;">GitHub</a></br>
			<a href="https://www.instagram.com/shafayet.bhuiyan" style="color:#FF4500; font-size: 20px;">Instagram</a>
									
		  </br></br>
		  
      </div>
      <!-- PROFILE CONTENT --> 
      <div id="content_container">				
        <div class="block">
          <h1>Education</h1>
          <blockquote class="slide-left">
              <h4>Southeast University, Dhaka</h4>
              <p>Bachelor in Computer Science and Engineering</p>
              
        </div>
        
        <div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
        
        <div class="block">
          <h1 id="skills">Skills</h1>
          <!-- <blockquote> -->
            <h4>Programming Language</h4>
            <ul class="list-horizontal">
              <li>C</li>
              <li>C++</li>
            </ul>
          <!-- </blockquote> -->
          <h4>Scripting Language</h4>
          <ul class="list-horizontal">
            <li>HTML</li>
            <li>CSS</li>
          </ul>
          
        </div>

        <div class="clear"></div>
        
        <div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
		
		
		<div class="block">
          <h1 id="awards">Awards</h1>
          <blockquote class="award">
            <h4>Financial Aid</h4>
            <p><b>Description: </b> Recieved waiver on tuition fee from Southeast University, based on merit for 4 semesters.</p>
          </blockquote>
        </div> 
      </div>
      <!-- <div class="horizontal_line">
        <div class="line_left"></div>
        <div class="left_circle"></div>
        <div class="central_circle"></div>
        <div class="right_circle"></div>
        <div class="line_right"></div>
      </div> -->
      <div class="clear"></div>
      <!-- FOOTER -->
      <div id="footer">

      </div>
</div>
 <!-- <script src="./Welcome!_files/jquery-3.5.0.min.map"></script>
  <script src="./Welcome!_files/index.js.download"></script>-->







</body></html>
