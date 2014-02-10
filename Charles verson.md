<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>WDI Prework</title>
  </head>
  <body>
    <header role="banner">
      <h1 id="logo">WDI Prework</h1>
      <nav id="site-navigation" role="navigation">
        <h2>Site navigation</h2>
        <!-- links to topic headings here -->
      </nav>
    </header>
    <main role="main">
      <aside id="sidebar">
        <h2>Sidebar</h2>
        <nav role="navigation">
          <h3>Topic/page navigation</h3>
          <!-- tree of links here -->
        </nav>
      </aside>
      <article id="lesson">
        <header>
          <h2>Lesson: Wireframing and review</h2>
        </header>
        <section id="lesson-objectives">
          <h3>Lesson objectives</h3>
          <ul class="objectives">
            <li>Learn the basics of website wireframing and why we do it</li>
            <li>Wireframe a few pages</li>
            <li>
              Learn a bit more about <em>sectioning content</em> and the
              &lt;nav&gt;, &lt;article&gt;, and &lt;aside&gt; tags
            </li>
            <li>Get a little bit deeper into ARIA roles</li>
            <li>Take a bit of a break</li>
          </ul>
        </section>
        <section id="introductory-material">
          <h3>Introductory material</h3>
          <p>
            OK, I don't know about you, but I'm tired of that boring Mojo site.
            I want to build something that's useful to me (or us). So, I'm thinking,
            let's build a website for the pre-work. We can go through the process
            step by step.
          </p>
          <p>
            At first, at least, it will just be an old-fashioned static website.
            But maybe later we'll add some CoffeeScript and jQuery and have some fun.
          </p>
        </section>
        <section id="getting-started">
          <h3>Hooray! So how do we get started?</h3>
          <p>
            Well, the first thing we need to do is to figure out what our site will do,
            and who it will do it for.
          </p>
          <p>
            To this end, we'll begin by creating personas for our audience. I can think
            of three different types of user who we might want to serve.
          </p>
          <p>
            Obviously, there are the students: you. You are the primary audience as you'll
            be doing the lessons, so the site should put your needs foremost.
          </p>
          <p>
            Then there are the instructors, who are also the authors and editors of the
            content. We'll need to think about them a bit, too.
          </p>
          <p>
            Finally, we might want to show the site off to others: friends, family, the
            course manager, curriculum folks, etc. Let's call them guests. So we should
            at least consider their needs.
          </p>
          <p>
            So we'll create three personas&mdash;student, instructor, and guest&mdash;one for each
            type of user.
          </p>
        </section>
        <section id="building-personas">
          <h3>Great! How do we build a persona, then?</h3>
          <p>
            Well, there is <a href="http://1.usa.gov/1cZZfj6">an excellent explanation of personas</a>
            on <a href="http://usability.gov/">the usability.gov website</a>, so rather than reinvent the
            wheel here, go check it out, then come back and we'll build our personas.
          </p>
          <p>
            So let's take a look at our three example personas...
          </p>
        </section>
        <section id="three-personas">
          <h3>Our three brilliant personas</h3>
          <figure id="student-persona">
            <figcaption>Student persona</figcaption>
            <dl class="persona">
              <dt>Persona</dt>
              <dd>Student</dd>

              <dt>Photo</dt>
              <dd>
                <img src="" width="" height="" alt="">
              </dd>

              <dt>Fictional name</dt>
              <dd>Sally Student</dd>

              <dt>Major responsibilities</dt>
              <dd>Learn web development skills as quickly as possible</dd>

              <dt>Demographics</dt>
              <dd>
                <ul>
                  <li>31 years old</li>
                  <li>Single</li>
                  <li>No children</li>
                  <li>B.S. Economics</li>
                  <li>Well traveled</li>
                  <li>A bit of an autodidact</li>
                  <li>Changing careers</li>
                </ul>
              </dd>

              <dt>Goals and tasks</dt>
              <dd>
                <p>
                  Excited about changing careers, but worried about whether she
                  can succeed in a new field.
                </p>
                <p>
                  Wants to learn as much as possible, but not sure where to start.
                </p>
                <p>
                  Has tried learning online. Now trying a more structured method.
                  Wants a job with a new startup upon graduation.
                </p>
              </dd>

              <dt>Environment</dt>
              <dd>
                <p>
                  Has grown up using computers and the Internet. Is comfortable
                  with technology.
                </p>
                <p>
                  Uses Facebook, Twitter, LinkedIn, Pinterest, and a dozen other
                  Web services. Spends at least an hour a day online.
                </p>
                <p>
                  Can type 40+ wpm. Has a decent laptop and an iPhone. Stays up
                  to date on software.
                </p>
              </dd>

              <dt>Quote</dt>
              <dd>
                <q>I hope I can keep up with the work!</q>
              </dd>
            </dl>
          </figure>
          <figure id="instructor-persona">
            <figcaption>Instructor persona</figcaption>
            <dl class="persona">
              <dt>Persona</dt>
              <dd>Instructor</dd>

              <dt>Photo</dt>
              <dd>
                <img src="" width="" height="" alt="">
              </dd>

              <dt>Fictional name</dt>
              <dd>Irving Instructor</dd>

              <dt>Major responsibilities</dt>
              <dd>Teach web development skills in an immersive setting</dd>

              <dt>Demographics</dt>
              <dd>
                <ul>
                  <li>28 years old</li>
                  <li>Married</li>
                  <li>No children</li>
                  <li>B.S. Informatics</li>
                  <li>Well traveled</li>
                  <li>An autodidact</li>
                  <li>A bit of a geek</li>
                </ul>
              </dd>

              <dt>Goals and tasks</dt>
              <dd>
                <p>
                  Wants to make WDI the best possible experience for the
                  students.
                </p>
                <p>
                  Always looking to improve the curriculum and to find more
                  effective and efficient ways to teach the material.
                </p>
                <p>
                  Works hard to keep up to date on the latest frameworks and APIs.
                </p>
              </dd>

              <dt>Environment</dt>
              <dd>
                <p>
                  Spent three years working for a large corporation after graduating
                  from the University of Syracuse with a degree in Informatics.
                </p>
                <p>
                  Worked four more years as a freelancer before getting involved in
                  the startup community.
                </p>
                <p>
                  Has given several seminars at various conventions. Seminars
                  generally well attended.
                </p>
                <p>
                  Has all the latest gear and keeps everything up to date.
                </p>
              </dd>

              <dt>Quote</dt>
              <dd>
                <q>Let's just roll our own and build it from scratch!</q>
              </dd>
            </dl>
          </figure>
          <figure id="guest-persona">
            <figcaption>Guest persona</figcaption>
            <dl class="persona">
              <dt>Persona</dt>
              <dd>Guest</dd>

              <dt>Photo</dt>
              <dd>
                <img src="" width="" height="" alt="">
              </dd>

              <dt>Fictional name</dt>
              <dd>Gertrude Guest</dd>

              <dt>Major responsibilities</dt>
              <dd>Curious as to what all the hoopla is about. Works in marketing.</dd>

              <dt>Demographics</dt>
              <dd>
                <ul>
                  <li>37 years old</li>
                  <li>Married</li>
                  <li>Mother of two</li>
                  <li>M.S. Marketing, M.B.A.</li>
                  <li>Likes to stay home</li>
                  <li>Impressed by good graphic design</li>
                  <li>Knows a bit about user experience</li>
                </ul>
              </dd>

              <dt>Goals and tasks</dt>
              <dd>
                <p>
                  Went back to school for an MBA when her kids were old enough
                  to go to school full day.
                </p>
                <p>
                  Eventually, wants to start her own company, but too addicted to
                  her current large income and prestigious position.
                </p>
                <p>
                  Judges websites by how they look and feel&mdash;by the UX.
                </p>
              </dd>

              <dt>Environment</dt>
              <dd>
                <p>
                  Not entirely comfortable with technology, but comfortable enough.
                </p>
                <p>
                  Uses a large display on her work desktop, which is a powerful
                  Mac with graphics capabilities.
                </p>
                <p>
                  Has a MacBook Air she uses on trips. Good with various
                  applications (PhotoShop, etc.), but knows nothing about coding.
                </p>
                <p>
                  Has an iPhone and knows how to use it. Your site better be
                  responsive!
                </p>
              </dd>

              <dt>Quote</dt>
              <dd>
                <q>Check out the cool new site I discovered!</q>
              </dd>
            </dl>
          </figure>
        </section>
        <section id="should-we-use-personas">
          <h3>Should we really use personas?</h3>
          <p>
            Well, that seems a funny question to ask at this juncture. I mean, we
            just spent a bunch of time making them up (well, I did, anyway). Now
            we're not going to use them?
          </p>
          <p>
            Heh, heh. Not so fast! We might use them, and we might not. It was important
            to create them if for no other reason than because there is a very good chance
            that whatever job you take in the webdev world, you're going to encounter them.
            Better to know how to make them.
          </p>
          <p>
            But there is a minority of developers who think that personas are a bad idea,
            and they make some very good points. One of the best points is that the personas
            are made up, and because we are just making them up, we tend fill them with our
            own stereotypes of our users and then fool ourselves into thinking that we know
            something about our users!
          </p>
          <p>
            Gosh, who would do a thing like that? Oh. Yeah. Everyone.
          </p>
          <p>
            Once the personas have been created, most developers will create user stories
            next. But these, too, have their detractors. Let's look at a couple of different
            ways to create user stories, and then see how else we might solve the same problem.
          </p>
        </section>
        <section id="job-stories">
          <h3>So what's the (user) story?</h3>
          <p>
            We need some way to come up with a specification for our website. One of the biggest
            mistakes that most newbie developers (and many who really oughta know better) make is to
            jump straight into coding.
          </p>
          <p>
            As you will soon discover&mdash;if you haven't already&mdash;the compulsion to do this is almost
            irresistible. I&mdash;cough, cough&mdash;may have even done it myself on occasion.
          </p>
          <p>
            But jumping straight to the code is what we in the biz call a Very Bad Idea™. Just.
            Don't. Do. It.
          </p>
          <p>
            What's the point of spending a lot of time writing code if you're just going to end up throwing it
            all away and redoing it?
          </p>
          <p>
            Here's the right way to build a website or Web application:
          </p>
          <ol>
            <li>Determine who your primary audiences are and what they want (Personas? Maybe.)</li>
            <li>
              Determine what your site/application needs to do to meet their needs (User stories?
              Job stories? Hmm. We'll see.)
            </li>
            <li>Wireframe out the first few pages</li>
            <li>Get buy in from the stakeholders</li>
            <li>Now, and only now, write a little bit of code, then iterate through the above again.</li>
          </ol>
          <p>
            This iterative process (called the Agile Method) allows us to make sure that all the
            stakeholders are involved at every step of the process, and that mistakes are discovered
            and corrected quickly. We'll be talking a lot about Agile during WDI. Wait! Talking? We'll
            be doing Agile. Daily.
          </p>
        </section>
        <section id="how-stories-look">
          <h3>Well, what do these stories look like?</h3>
          <dl class="story-formats">
            <dt>The original format from 2001 looked like this:</dt>
            <dd>As a [role], I want [goal/desire] so that [benefit]</dd>

            <dt>Here's an example (from Wikipedia):</dt>
            <dd>
              As a student, I want to see estimated times for completion, so that I may
              schedule my lesson better.
            </dd>

            <dt>
              Some developers have a problem with this format, however. They think that
              the benefit should come first (calling it &ldquo;hunting the value&rdquo;), so they swap
              it around:
            </dt>
            <dd>In order to [receive benefit] as a [role], I want [goal/desire]</dd>

            <dt>Now we have:</dt>
            <dd>
              So that I may schedule my lessons better, as a student, I want to see estimated
              times for completion.
            </dd>

            <dt>
              That worked for a number of years. Then some smart guy pointed out that if you
              drop the role part, you don't really lose anything. And then that lead to yet
              another idea, that of the job story. The job story follows this format:
            </dt>
            <dd>When [situation], I want to [motivation], so I can [expected outcome]</dd>

            <dt>Here's our user story rewritten as a job story:</dt>
            <dd>
              When I start a lesson, I want to know how long it will take to complete it,
              so that I can schedule my time appropriately.
            </dd>
          </dl>
        </section>
        <section id="choosing-a-story-format">
          <h3>OK, I give up. Which story format should I use?</h3>
          <p>
            The truth is this: it probably doesn't matter. What is most important here is to
            stimulate discussion involving all the stakeholders&mdash;including, if possible, the
            users themselves&mdash;so that the specification&mdash;the feature set&mdash;is as complete and
            correct as possible.
          </p>
          <p>
            Building the pre-work website is an Agile process&mdash;an iterative process&mdash;so why
            not write a few of your own user or job stories? After all, you are the intended
            users. Send yours to
            <a href="mailto:charles.munat@generalassemb.ly">charles.munat@generalassemb.ly</a>
            and maybe they'll be incorporated into the site's UX. Stranger things have happened...
          </p>
        </section>
        <section id="the-wireframe">
          <h3>On to the wireframe!</h3>
          <p>
            OK, assuming we have an idea of who our audience(s) is, and we have a few stories
            to let us know what features we want, the next step is to create a basic wireframe
            of the site. In this lesson we're just going to build a structure, then we'll fill
            it in with an example lesson in our next pre-work installment.
          </p>
          <p>
            According to Wikipedia (a very useful resource and one I recommend highly):
            <q cite="http://en.wikipedia.org/wiki/Website_wireframe">
              A website wireframe, also known as a page schematic or screen blueprint,
              is a visual guide that represents the skeletal framework of a website.
            </q>
          </p>
          <p>
            I used <a href="http://balsamiq.com/">an online wireframing tool called Balsamiq</a>
            to create a very simple structural wireframe for a typical lesson page. Here it is:
          </p>
          <figure id="example-page-basic-wireframe">
            <figcaption>Example page basic wireframe</figcaption>
            <img src="" width="" height="" alt="">
          </figure>
        </section>
        <section id="why-so-sketchy">
          <h3>Wait... why does it look so, uh, sketchy?</h3>
          <p>
            That's not an accident! Avoid the temptation to use &ldquo;pixel perfect&rdquo; graphics for
            your wireframes! You are not doing the graphic design here. You are working on the
            structure and layout of the page&mdash;determining what goes where.
          </p>
          <p>
            If you use something like PhotoShop and you try to make it look like it will look
            with all the design elements in place, then you are getting way ahead of yourself
            and wasting a lot of time. Odds are that this design is going to change many times
            before it is finalized. You really want to waste all that time? Keep it to simple
            sketches until we know what we're going to do.
          </p>
          <p>
            Create an index.html page and code the above structure up (without looking), then
            check your code against mine (see last page). No cheating!
          </p>
        </section>
        <footer role="presentation">
          <section id="success-measures">
            <h4>Measuring successful lesson completion</h4>
            <p>Hopefully, you've come away from this lesson understanding:</p>
            <ul class="measures">
              <li>How to create user <em>personas</em> and why</li>
              <li>What the pros and cons are of <em>personas</em></li>
              <li>
                That the most important thing is not the personas, but
                <em>understanding the needs and wants of your users</em>
              </li>
              <li>How to write user stories</li>
              <li>
                That there are several different formats for user stories,
                and little agreement on <em>how</em> to do them, but near
                complete agreement that you need to do <em>something</em>
                to determine your website's feature set and make sure it
                addresses the needs of your users
              </li>
              <li>
                What a wireframe is, why it looks the way it does, and what
                it is used for
              </li>
            </ul>
          </section>
          <section id="lesson-faq">
            <h4>Frequently asked questions</h4>
            <dl class="faq">
              <dt>
                Is it just me, or does Irving look a little like Jackie Chan?
              </dt>
              <dd>
                It's just you.
              </dd>
              <dt>
                Do I really have to go through all this trouble? Can't I just
                start coding?
              </dt>
              <dd>
                Of course you can just jump into the coding. All shitty web
                developers do. Just admit that you suck, and you can skip all
                these formalities. Unfortunately, if &ldquo;suck&rdquo; is not the adjective
                you had in mind to describe your skill set, well, no, you can't
                really skip these steps.
              </dd>
              <dd>
                Sorry to be the one to have to break it to you.
              </dd>
            </dl>
          </section>
          <section id="additional-resources">
            <h4>Additional resources</h4>
            <ul class="resources">
              <li><a href="http://1.usa.gov/1cZZfj6">Personas</a></li>
              <li><a href="http://bit.ly/KlG8ne">Why personas suck</a></li>
              <li><a href="http://bit.ly/1ak8HYJ">User stories</a></li>
              <li><a href="http://bit.ly/KkdHXk">User story tips</a></li>
              <li><a href="http://bit.ly/19CiJKe">Who does what</a></li>
              <li><a href="http://bit.ly/JKTKHW">Job stories</a></li>
              <li><a href="http://bit.ly/1gbtzWg">Wireframes</a></li>
              <li><a href="http://bit.ly/1dVb1aP">A pretty good guide to wireframing</a></li>
              <li><a href="http://balsamiq.com/">Balsamiq</a></li>
            </ul>
          </section>
        </footer>
      </article>
    </main>
    <footer>
      <section id="copyright">
        <h2>Copyright</h2>
        <!-- site copyright here -->
      </section>
      <nav id="site-map" role="navigation">
        <h2>Site map</h2>
      </nav>
    </footer>
    <section id="contact">
        <h2>Contact info</h2>
      <!-- contact info here -->
    </section>
  </body>
</html>