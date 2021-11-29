# portfolio
<!DOCTYPE html>
<html>

<head>
	<title>
		Create a Portfolio Gallery
		using HTML and CSS
	</title>
	
	<meta name="viewport"
		content="width=device-width, initial-scale=1">
		
	<style>
	
		/* wildcard styling */
		* {
			box-sizing: border-box;
		}
		
		/* padding for whole body */
		body {
			padding: 15px;
		}
		
		/* styling body */
		.container {
			max-width: 1200px;
			margin: auto;
		}
		
		h1 {
			color: rgba(7, 182, 30, 0.308);
		}
		
		/* anchor tag decoration */
		a {
			text-decoration: none;
			color: #e63039;
		}
		
		a:hover {
			color: rgb(225, 173, 230);
		}
		
		/* paragraph tga decoration */
		p {
			display: -webkit-box;
			-webkit-box-orient: vertical;
			-webkit-line-clamp: 4;
			overflow: hidden;
	
		}
		
		/* row and column decoration */
		.row {
			margin: 0px -18px;
			padding: 8px;
		}
		
		.row > .column {
			padding: 6px;
		}
		
		.column {
			float: left;
			width: 25%;
		}
		
		.row:after {
			content: "";
			display: table;
			clear: both;
		}
		
		/* content decoration */
		.content {
			background-color: white;
			padding: 10px;
			border: 1px solid rgb(17, 0, 255);
		}
		
		/* window size 850 width set */
		@media screen and (max-width: 850px) {
			.column {
				width: 50%;
			}
		}
	
		/* window size 400 width set */
		@media screen and (max-width: 400px) {
			.column {
				width: 100%;
			}
		}
	</style>
</head>

<body style="background-color: wheat;">
	
	<!-- title and tag -->
	<div class="container">
		<h1>MANDA SASANK SAI</h1>
		<h3>Vellore instute of technology , AP , 2021-2025, CSE</h3>
        <img src=
"https://lh3.googleusercontent.com/XdGQUc0wQwmiKuokyO5QK-fYTf6L05_u0HJdRLwpaU5aoaGQWKNEoHTsx_JTMbtkq-LYiw=s85"
						alt="" style="width:20%">
		<hr>

		<!-- Content of the body-->
		<h2>ABOUT ME</h2>
        <p>Myself Sasank sai manda i'm pursuing engineering at VIT-AP. i studied at sri chaitanya institutions and completed my 10TH and 12TH classes . I have a little knowledge of poster making and content writing. i'm intrested in web development.
            i'm working with CSI as a special mention member and i'm looking forward to learn things and create . 

        </p>
		<div class="row">
			<div class="column">
				<div class="content">
					
					
                            </h3>
                    <h3>
                        <a href="#">Hobbies</a>
                        <p> POSTER MAKING ,CONTENT WRITING ,Music and Movies</p>
                        </h3>


				</div>
			</div>
			
			<div class="column">
				<div class="content">
					<img src=
"https://i2.wp.com/geoawesomeness.com/wp-content/uploads/2017/09/Coding-Geospatial.jpg?fit=1152%2C768&ssl=1"
						alt="" style="width:100%">
                        <a href="#">Skills</a>
					
					

                        <p>
                                            LEARNING PYTHON,
                                            HTML AND CSS  ,
                                            FIGMA AND PTT 
                                                    </p>


				</div>
			</div>
			
			<div class="column">
				<div class="content">
					<img src=
"https://www.anandgroupindia.com/wp-content/uploads/2019/05/contactus.jpg"
						alt="" style="width:100%">
					<h3>
						<a href="#">Contact</a>
                        <p>
                            9492629058
                        </p>
					</h3>
                    <a href="#">Mail </a>
                    <p>sasanksaimanda@gmail.com</p>
					
					




				</div>
			</div>
			
			<div class="column">
				<div class="content">
					<img src=
"https://www.akvertise.com/wp-content/uploads/2017/03/FBIG.jpg"
						alt="" style="width:100%">
					<h3>
						<a href="#">Social Media</a>
					<p>
                        <a href="#">instagram </a> 
						<p> sasankkkk </p>
                     
                        <a href=https://www.facebook.com/profile.php?id=100075106603862 >facebook - click here</a> 
                        </p>
                        </h3>
					
					




				</div>
			</div>
		
	
</body>

</html>		
