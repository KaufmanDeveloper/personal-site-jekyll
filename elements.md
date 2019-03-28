---
layout: page
title: Projects
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Projects</h1>
		</header>

<!-- Content -->
<h2 id="content">Knoxville Utilities Board</h2>
<p>The constantly evolving nature of web development is endlessly exciting. Every day
I get to wake up and be excited to go to work and learn new things. Over my first year and a half being
a developer I've worked on many projects for Knoxville Utilities Board.</p>
<div class="row">
	<!-- Break -->
	<div class="4u 12u$(medium)">
		<h3>Automated Deployment Application</h3>
		<p>Using Ember.js and Mirage to simulate back end services, I built a responsive deployment application to allow for our deployments to be automated via a web application. I used Java web services calling Github's API via GraphQL to gather information about a given release's deployment data. Using this data I populated deployable list items that at a push of a button would allow deployment operators to deploy applications at a given release to the given application environment. </p>
	</div>
	<div class="4u 12u$(medium)">
		<h3>Email Template Architecture</h3>
		<img src="assets/images/email-template.png" alt="" data-position="center center" />
		<p>Using an fork of Sparkbox's <a href="https://github.com/sparkbox/email-lab" target="_blank">email lab</a> I built responsive email templates that I then used Handlebars replacement syntax a Java web service to unify all KUB automated e-mails through one web service. I then wrote a node script that our Jenkins CI could use to build a deployment artifact containing our built email templates in one file. This then was used to deploy releases of our email templates through our deployment application.</p>
	</div>
	<div class="4u$ 12u$(medium)">
		<h3>Timesheet Application</h3>
		<p>I implemented Peoplecode and exposed SOAP service endpoints to allow for Java REST endpoints to expose timesheet data and allow KUB employees to enter timesheet data via our main apps landing page.</p>
	</div>
</div>

<h2 id="content">Personal Projects</h2>

<p>I've worked on a number of personal projects as I've gained experience as a developer. ABC: Always Be Coding is a principle I live by, and keeps my passion for development strong.</p>

<div class="row">
	<!-- Break -->
	<div class="4u 12u$(medium)">
		<h3>Gradezilla</h3>
		<img src="assets/images/gradezilla.png" alt="" data-position="center center" />
		<p>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</p>
	</div>
	<div class="4u 12u$(medium)">
		<h3>Gravity Flyer</h3>
		<img src="assets/images/gravity-flyer.png" alt="" data-position="center center" />
		<p>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</p>
	</div>
	<div class="4u$ 12u$(medium)">
		<h3>Sword Runner</h3>
		<p>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</p>
	</div>
</div>

</div>
</section>

</div>
