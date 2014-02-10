wireframe
=========

<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>wireframe</title>
	</head>
	<body>
		<header role="banner">
			<h1 id="logo">WDI PreWork</h1>
			<nav id="site_navigation" role="navigation">
				<h2>Site Navigation</h2>
				<!--add navigation links here -->
			</nav>
		</header>
		<main role="main">
			<aside id="sidebar">
				<h2>sidebar</h2>
				<nav role="navigation">
					<h3>tree_navigation</h3>
					<!-- add navigation links here -->
				</nav>
			</aside>
			<article id="lessons">
				<header>
					<h2>Lesson: Wireframing and Review</h2>
					<section id="lesson-objectives">
						<h3>Lesson Objectives</h3>
						<ul>
							<li>Learn the basics of websites and Why</li>
							<li>Wireframe a few pages</li>
							<li>Learn about <em>sectioning content</em> and the  &lt;nav&gt;,  &lt;article&gt;  and  &lt;aside&gt;  tags</li>
							<li>Get a little deeper into ARIA roles</li>
							<li>Take a break</li>
						</ul>
					</section>
					<section id="intro">
						<h3>Introduction</h3>
						<p>OK,I don't know about you, but I'm reired of that boring Mojo site.  I want to build someting that's useful to me (or us).  So, I'm thinking <em>let's build a website for the pre-work</em>.  We can go through the process step by step.</p>
						<p>At first, at least, it will just ban an olf-fashined static website.  But maybe later we'll add some CoffeeScript and jQuery and have some fun.</p>
					</section>
					<section id="getting-started">
						<h3>Hooray! So how do we get started?</h3>
						<p>Well, the first thing we need to do is to gifure out what our site will do and who it will do it for.</p>
						<p>To this end, we'll begin by creating <em>personas</em> for our audience.  I can think of three different types of user who we might want to serve.</p>
						<p>Obviously, there are the <em>students</em>: you.  You are the primary audience as you'll be doing the lesson, so the site should put your needs foremost.</p>
						<p>Then there are the <em>instructors</em>, who are also the authors and editors of the content.  We'll need to think about them a bit, too.</p>
						<p>Finally, we might want to show the site off to others: friends, family, the course manager, curriculum folks, etc.  Let's call them <em>guests</em>.  So we should at least consider their needs</p>
						<p>So we'll creat three <em>personas</em> - student, instructor and guest - one for each type of user.</p>
					</section>
					<section id="building-personas">
					<h3>Great!  How do we build a <em>persona</em> then?</h3>
						<p>Well, there's an excellent explanation on the <i>usability.gov</i> website, so rather than reinvent the wheelhere, we'll just linke to that.  Go check it, then come back and we'll build our personas.</p>
						<a href="http://www.usability.gov/how-to-and-tools/methods/personas.html">usability website</a>
						<p>So let's tak a look at our three example personas...</p>
					</section>
					<section id="Persona-WDI">
						<h3>Persona: Student</h3>
						<dl class="student">
							<dt>Persona</dt>
							<dd>WDI Student</dd>
							<dt>Photo</dt>
							<dd><!--add photo here --></dd>
							<dt>Fictional name</dt>
							<dd>Sally Student</dd>
							<dt>Major responsibilities</dt>
							<dd>Learn web development skill as quickly as possible.</dd>
							<dt>Demographics</dt>
							<dd>31 years old</dd>
							<dd>Single</dd>
							<dd>No children</dd>
							<dd>B.S.Economics</dd>
							<dd>Well travelled</dd>
							<dd>A bit of an autodidact</dd>
							<dd>Changing careers</dd>
							<dt>Goals and tasks</dt>
							<dd>Excited about canging careers, bu worried about whether she can succeed in a new field.</dd>
							<dd>Wants to learn as much as possible, but not sure where to start.</dd>
							<dd>Has tried learning online.  Now trying a more structured method.</dd>
							<dd>Want a job with a new startup upon graduation.</dd>
							<dt>Environment</dt>
							<dd>Has grown up using computers and the internet.  Is comfortable with technology.</dd>
							<dd>Uses Facebook, Twitter, LinkedIn, Pinterest and a dozen other web services.  Spends at least an hour a day online.</dd>
							<dd>Can type 40+wpm.  Has a decent laptop and an iphone.  Stays up to date on software.</dd>
							<dt>Quote</dt>
							<dd>I hope I can keep up with the work.</dd>
						</dl>
					</section>
				</header>
				<section>
					<h3>Section Title</h3>
					<!-- main article content here -->
					<aside role="note">
						<h4>Note</h4>
						<!-- parenthetical commentary here -->
					</aside>
				</section>
				<footer>
					<h3>Footer title</h3>
					<section id="success-measures">
						<h4>Measuring successful completion of this lesson</h4>
						<p>Hopefully, you've come away from this lesson understanding:</p>
						<ul class="measures">
							<li>How to create user <em>Personas</em> and why</li>
							<li>What the pros and cons are of <em>Personas</em></li>
							<li>That the most important thing is the Personas, but <em>understanding the needs and wants of your users</em></li>
							<li>How to write User Stories</li>
							<li>That there are several different formats for User Stories and little agreement on <em>how</em> to do them, but near complete agreement that you need to do <em>something</em> to determine your website's geature set and make sure it addressed the needs of your users</li>
						</ul>
					</section>
					<section id="lesson-faqs">
						<h4>Frequently Asked Questions</h4>
						<dl class="faqs">
							<dt>Is it just me, or does Irving look a little like Jackie Chan?</dt>
						<dd>It's just you</dd>
						<dt>Do I really have to go through all this trouble?  Can't I just start coding?</dt>
						<dd>Of course you can just jump into the coding.  All shitty web developers do,  Just admit that you suck and you can skip all of these formalities.  Unfortunately, if "suck" is not the adjective you had in mind to describe your skill set, well, no, you can't really skip these steps.</dd>
						<dd>Sorry to be the one to have to break it to you.</dd>
						</dl>
					</section>
					<section id="additional-resources">
						<h4>Additional Resources</h4>
						<ul class="resources">
							<li><a href="http://1.usa.gov/1cZZfj6">Personas</a></li>
							<li><a href="http://bit.ly/KlG8ne">Why Personas Suck</a></li>
							<li><a href="http://bit.ly/1ak8HYJ">User Stories</a></li>
							<li><a href="http://bit.ly/KkdHXk">User Story Tips</a></li>
							<li><a href="ttp://bit.ly/19CiJKe">Who does what?</a></li>
							<li><a href="http://bit.ly/JKTKHW">Job stories</a></li>
							<li><a href="http://bit.ly/1gbtzWg">Wireframes</a></li>
							<li><a href="http://bit.ly/1dVb1aP">A gretty good guide to wireframing</a></li>
							<li><a href="http://balsamiq.com/">Balsamiq</a></li>
						</ul>
					</section>
				</footer>
			</article>
		</main>
		<footer>
			<section id="copyright">
				<h2>copyright</h2>
				<!-- add copyright link here -->
			</section>
			<nav id="site_map" role="navigation">
				<h2>site_map</h2>
			</nav>
		</footer>
		<section id="contact">
			<h2>Contact</h2>
		</section>
	</body>
</html>
