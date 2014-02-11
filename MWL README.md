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
						<p>Well, there's an excellent explanation on the <a href="http://www.usability.gov/how-to-and-tools/methods/personas.html">usability.gov website</a>, so rather than reinvent the wheelhere, we'll just linke to that.  Go check it, then come back and we'll build our personas.</p>
						<a href="http://www.usability.gov/how-to-and-tools/methods/personas.html">usability.gov website</a>
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
					<section id="Persona-instructor">
						<h3>Persona: Instructor</h3>
						<dl class="instructor">
							<dt>Persona</dt>
							<dd>WDI Instructor</dd>
							<dt>Photo</dt>
							<dd><!-- add photo here -->
							<dt>Fictional name</dt>
							<dd>Irving Instructor</dd>
							<dt>Major responsibilities</dt>
							<dd>Teach web eveloment skill an an immersive setting.</dd>
							<dt>Demographics</dt>
							<dd>28 years old</dd>
							<dd>Married</dd>
							<dd>No children</dd>
							<dd>B.S.Informatics</dd>
							<dd>Well travelled</dd>
							<dd>An autodidact</dd>
							<dd>A bit of a geek</dd>
							<dt>Goals and tasks</dt>
							<dd>Want to make WDI the best possible experience for students.</dd>
							<dd>Always looking to improve the curriculum and to find more effective and efficent ways to teach the material.</dd>
							<dd>Works hard to keep up to date on the latest frameworks and APIs.</dd>
							<dt>Environment</dt>
							<dd>Spent three years working a large coroporation after graduating from University of Syracuse, with a degree in Informatics.</dd>
							<dd>Workded forur more ears a a freelancer before getting involved in the startup community.</dd>
							<dd>Has given several seminar at varous conventions.  Seminars generally well attended.</dd>
							<dd>Has all of the latest gear and keep everything up to date.</dd>
							<dt>Quote</dt>
							<dd>Let's just roll our own and build it from scratch!</dd>
						</dl>
					</section>
					<section id="persona-guest">
					<h3>Persona: Guest</h3>
						<dl class="guest">
							<dt>Persona</dt>
							<dd>Guest</dd>
							<dt>Photo</dt>
							<dd><!-- add photo here -->
							<dt>Fictional name</dt>
							<dd>Getrude Guest</dd>
							<dt>Major responsibilities</dt>
							<dd>Curious as to what all the hoopla is about.  Works in marketing.</dd>
							<dt>Demographics</dt>
							<dd>37 years old</dd>
							<dd>Married</dd>
							<dd>Mother of two</dd>
							<dd>M.S.Marketing, MBA</dd>
							<dd>Likes to stay home</dd>
							<dd>Impressed be good graphic design</dd>
							<dd>Knows a bit about user experience</dd>
							<dt>Goals and tasks</dt>
							<dd>Went back to school for an MBA when her kids were old enough to go to school full day.</dd>
							<dd>Eventually wants to start her own company, but too addicted to her current large income and prestigious position</dd>
							<dd>Judges websites by how they look and feel - by the UX.</dd>
							<dt>Environment</dt>
							<dd>Not entirely comfortable with technology, but comfortable enough.</dd>
							<dd>Uses a large dispay on her desktop, which is a powerful Mac with graphics capabilities.</dd>
							<dd>Has a MacBook Air she uses on trips,  Good with varous applications, (photoshop, etc), but knows nothing about coding.</dd>
							<dd>Has an iPhone and knows how to use it.  Your site better be responsive!</dd>
							<dt>Quote</dt>
							<dd>Check out the cool new site I discovered.</dd>
						</dl>
					</section>
					<section id="Should-we-use-personas">
						<h3>Should we really use persona?</h3>
						<p>Well, that seems a funny question to ask at this juncture.  I mean, we just spent a bunch of time making them up (well, I did, anyway).  Now we're not going to use them?</p>
						<p>Heh, heh.  Not so fast!  We <em>might</em> use them and we might not.  It was important to create them if for no toher reason that because there is a very good chance that whatever job you take in the webdev work, you're going to encounter them,  Better to know how to make them.</p>
						<p>But there is a minority of developers who think that spersonas are a <em>bad idea</em> and they make some very good points.  One of the best points is that the personas are <em>made up</em>, and because we are just making them up, we tend to fill them with our own <em>stereotypes</em> of our users and then fool ourselves into thinking that we know something about our users!</p>
						<p>Gosh, who would do a thing like that? Oh. Yeah.  Everyone.</p>
						<p>Once the personas have been created, most developers will create <em>user stories</em> next.  But these, too, haave their detractors.  Let's look at a couple of different ways to create user stories and then see how else we might solve the same problem.</p>
					</section>
					<section id="user-story">
					 	<h3>So what's the story?</h3>
						 <p>We need some way to come up with a <em>specificatiom</em> for our website.  One of the biggest mistakes that most newbie developers 9and many who really oughta know better) make is to <em>jump straight into coding.</em></p>
						 <p>As you will soon discover, if you haven't already, the compulsion to do this is <em>almost irresistible</em>.  I -- cough, cough --may have even done it myself on occasion.</p>
						 <p>But jumping straight to the code is what we in the biz call a <strong>Very Bad Idea</strong>.  Just.  Don't.  Do.  It.</p>
						 <p>What's the point of spending a lot of time writing code <em>if you're just going to end up throwing it all away and redoing it?</em></p>
						 <p>Here's the right way to build a website or Web application:</p>
						 	<ol class="dev-process">
						 		<li>Determine who your <em>primary audiences</em> are and what they want (Personas?  Maybe.)</li>
							 	<li>Determine what your site/application <em>needs to do</em> to meet their needs (User stories?  Job stories?  Hmm..Well see.)</li>
							 	<li><em>Wireframe</em> out the first few pages.</li>
							 	<li>Get <em>buy in</em> from the stakeholders.</li>
							 	<li><strong>Now</strong>, and only now write <em>a little bit of code</em>, then <em>iterate</em> through the above again.</li>
							 </ol>
						<p>This iterative process (called <i>Agile Method</i>) allows us to make sure that all the stakeholders are involved at every sep of the process and thea mistakes are discover and dorrected quickly.  We'll be talking a lot about Agile during WDI?  <em>We'll be doing Agile.</em>  Daily.</p>
					</section>
					<section id="stories">
						<h3>Well, what do these stories look like?</h3>
						<p>The orginal format from 2001 looked like this:</p>
						<blockquote>As a [role], I want [goal/desire] so that [benefit]</blockquote>
						<p>Here's an example (from Wikipedia)</p>
						<blockquote>As a <em>student</em>, I want to see <em>estimated times for completion</em>, so that I may <em>schedule my lesson better.</em></blockquote>
						<p>Some developers have a problem with this format, however.  They think that the <em>benefit</em> should come first (calling it "hunting the value"), so they swap it around:</p>
						<blockquote>In order to [<em>receive benefit</em>] as a [<em>role</em>], I want [<em>goal/desire</em>]</blockquote>
						<p>Now we have:</p>
						<blockquote>So that I may <em>schedule my lesson better</em>, as a <em>student</em>, I want to <em>see estimated times for completion</em></blockquote>
						<p>That worked for a number of years.  Then some smart guy pointe out that if you drop the <em>role</em> part, you don't really lose anything.  And then tat lead to yet another idea, that of the <em>job story</em>.  The job story follwo this format:</p>
						<blockquote>When [<em>situation</em>], I want to [<em>motivation</em>], so I can [<em>expected outcome</em>].</blockquote>
						<p>Here's our user story rewritten as a job story:</p>
						<blockquote>When I star a lesson, I want to know <em>how long it will take to complete it</em>, so that I can <em>schedule my time</em> appropriately.</blockquote>
					</section>
					<section id="which-format">
						<h3>OK, I give up.  Which format should I use?</h3>
						<p>The truth is this: probable doesn't matter.  What is most important here is to <em>stimulate discussion</em> involving <em>all of the stakeholders</em> -- including, if possible, the users themselves -- so that the specification -- the <em>feature set</em> -- is as complete and correct as possible.</p>
						<p>Building the pre-work website is an <em>Agile</em> process --and <em>iterative</em> process-- so why not write a few of your own user or job stories?  After all, <em>you are the intended users</em>.  Send youres to charles.munat@generalassemb.ly and maybe they'll be incorporated into the site's UX.  Stranger things have happened...</p>
					</section>
					<section id="the-wireframe">
						<h3>On to the wireframe</h3>
						<p>OK, assuming we have an idea of who our audience(s) is, and we have a few stories to let us know what features we want, the next step is to create a basic <em>wireframe</em> of the site.  In this lesson we're just going to build a structure, then we'll fill it with an example lesson in our next pre-work installment.</p>
						<p>According toe Wikipedia (a very useful resource and one I recommend highly): "A <em>website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website".</em></p>
						<p>I used an online too called <cite>Balsamiq</cite> to creat a very simple structural wireframe for a typical lesson page (<a href="http://balsamiq.com">balsamiq.com</a>).  Here it is:</p>
						<!--add image here -->
						<p>Wait...why does it look so, uh, <em>sketchy?</em></p>
						<p>That's not an accident.  <em>Avoid the temptation to use "pixel perfect" graphics for your wireframes!</em>  You are not doing the graphic design here. You are working on the <em>structure</em> and <em>layout</em> of the page --determining <em>what</em> goes <em>where.</em></p>
						<p>If you use something like PhotoShop and you try to make it look like it will look with all of the design elements in place, <em>then you are getting way ahead of yourself and wasting a lot of time.</em>  Odds are that this design is going to change <em>many times</em> before it is finalised.  You really want to waste all that time?  <em>Keep it to simple sketches until we know what we're going to do.</em></p>
						<p>Create an index.html page and code the above structure up (without looking), then check your code against mine (see last page).  No cheating!</p>
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
							<li>That there are several different formats for User Stories and little agreement on <em>how</em> to do them, but near complete agreement that you need to do <em>something</em> to determine your website's feature set and make sure it addressed the needs of your users</li>
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
