<html>
<head>
	<title>Pansy's Portfolio</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		#TH {
 		width: 100%;
 		padding: 10px 20px;
  		text-align: left;
  		background-color: lightgrey;
  		margin-top: 20px;
		}
		#VC {
  		width: 100%;
  		padding: 10px 20px;
  		text-align: left;
  		background-color: lightgrey;
  		margin-top: 20px;
		
	</style>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>Hi, I'm Pansy.</h1>
		<nav>
			<ul>
				<p>Content:</p>
				<li><a href="#about">About Me</a></li>
				<li><a href="#workexperience">Work Experience</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h2>About Me</h2>
			<p>I'm an engineer turned marketer with 2+ years of experience. With a lust for articulating my knowledge, I dove into the world of content. Writing has always been an escape in this overachieving world. My journey of writing began as I started freelancing during the pandemic and eversince, I have grown into a full-fledged content marketer.</p>
			
			<p>If you're looking for well-researched and converting content, we can work together to create the story of your brand. With the incoming of AI language models like ChatGPT, the demand for quality content rises. Especially, those that Google favor. </p>
		</section>
		<section id="workexperience">
			<h2>Work Experience</h2>
			<h3>TurboHire</h3>
				<p>B2B | SaaS | An AI-powered recruitment automation and applicant tracking platform</p>
			<button onclick="myFunction1()">Show More</button>

			<div id="TH">
			<h4>Best Blogs</h4>
			<ul>
				<li><p><a href="https://turbohire.co/resources/blog/step-by-step-guide-to-boolean-search-in-candidate-discovery-of-hiring/" target="_blank">Boolean Search in Recruitment</a></p></li>
				<li><p><a href="https://turbohire.co/resources/blog/what-is-candidate-calibration-in-screening-stage-of-hiring/" target="_blank">Candidate Calibration in Hiring</a></p></li>
				<li><p><a href="https://turbohire.co/resources/blog/what-is-automated-one-way-interview-how-to-automate-interviews/" target="_blank">Automated One-Way Interview in Hiring</a></p></li>
				<li><p><a href="https://turbohire.co/resources/author/pansy/" target="_blank">View other blogs</a></p></li>
			</ul>
			<h4>Industry Reports</h4>
			<p>Industry report webpage copy | Report content structing, writing, and research</p>
			<ul>
				<li><p><a href="https://turbohire.co/resources/industry-reports/the-present-of-hiring/" target="_blank">Global Recruitment Industry Report 2022</a></p></li>
				<li><p><a href="https://turbohire.co/resources/industry-reports/guide-to-virtual-candidate-assessment-in-2022/" target="_blank">Guide to Virtual Candidate Assessment, 2022</a></p></li>
				<li><p><a href="https://turbohire.co/resources/industry-reports/top-5-use-cases-in-recruitment-automation/" target="_blank">Top 5 Use Cases of Recruitment Automation</a></p></li>
			</ul>
			<h4>HR Toolkit</h4>
			<p>A toolkit containing diverse and customizable templates of company policies, HR mails, interview questions, survey questionnaires, interview mails, hiring mails, etc. Organized, managed, and written by me. <a href="https://turbohire.co/hr-toolkit/" target="_blank">Check it out.</a></p>
			</div>	
			
        	<h3>Vantage Cicle</h3>
        	<p>B2B | SaaS | A one-stop employee engagement and employee benefits platform</p>
       	 	<button onclick="myFunction2()">Show More</button>

			<div id="VC">
        		<h4>Vantage Lens</h4>
        		<p>Vantage Circle recently launched a new product called "Vantage Lens", a workplace culture score generating platform.</p>
        		<p>How do I contribute?</p>
        		<ul>
        			<li><p>Content strategy and planning with the SEO Team</p></li>
            			<li><p>Writing SEO-optmized employee-centric blogs</p></li>
            			<li><p>Update and track keywords on SEMrush, Google Search Console, and AHREF.</p></li>
				<p><a href="https://www.vantagelens.com/blog/author/pansy/" target="_blank">View blogs</a></p>
			</ul>
			</div>
		</section>
		
		<section id="contact">
		<h2>Contact Me</h2>
		<ul>
			<li><p>Email: thakuriapansy@gmail.com</p></li>
			<li><p><a href="https://www.linkedin.com/in/pansythakuria/" target="_blank">LinkedIn profile</a></p></li>
			<li><p>Phone: 8638669512</p></li>
			<li><p><a href="Pansy Thakuria Resume 2023.pdf" download>Download my resume</a></p></li>
		</ul>
		</section>
		<footer>
			<p>Copyright © My Portfolio 2023.</p>
		</footer>
<script>
function myFunction1() {
  var x = document.getElementById("TH");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
function myFunction2() {
  var y = document.getElementById("VC");
  if (y.style.display === "none") {
    y.style.display = "block";
  } else {
    y.style.display = "none";
  }
}
</script>
</main>
</body>
</html>
