<!-- Render in python-markdown for best effect (https://github.com/waylan/Python-Markdown) -->
<style type="text/css">
	/**
	 * This width helps the browser view to better match printer output
	 */
	body {
		width: 45em;
	}

	/*
	 * Assign to a <p> to help control print layout
	 */
	.print-show {
		display: none;
	}

	h3 {
		margin: 0px !important;
		padding: 0px !important;
	}

	/**
	 * - PNG icons from https://www.flaticon.com/packs/font-awesome
	 * - PNG converted to base64 with https://www.base64-image.de/
	 */
	span#github::before {
		content: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAAAnNCSVQICFXsRgQAAAAJcEhZcwAAAHcAAAB3AZw8xOwAAAAZdEVYdFNvZnR3YXJlAHd3dy5pbmtzY2FwZS5vcmeb7jwaAAAA8ElEQVQoU33OsUrCARTF4S90F0KDBsWhwUkLWoK20t6g2dW9GqTAJwiK5giCth6g0XCQFmdRlzJdggYH3W6D2hL/OMvlnN85XOF/CRpuHP0JTtxpLIG2EB4dOnXmSt2xJyG0l8A4cf9jCbwmAu3Apq9E4FuW68Q4hFt6q7PrzcTCwsSb7srtMRMG9pQV1zVFZXsGwoyR0LRtbiwdgrSxuW1NYcSzcKAqhHwI8kKoOhCeuRTqcmaGUiFIGZrJqQuXbPnUl1GQ/f0hqyCj711WsKNtqqWmoqSkoqZlqqMU1p1d5x686Oh4ce/Cvo3wCyTrB+uNxaQpJPHSAAAAAElFTkSuQmCC');
	}

	span#so::before {
		content: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAAAnNCSVQICFXsRgQAAAAJcEhZcwAAAG8AAABvAfGi3EMAAAAZdEVYdFNvZnR3YXJlAHd3dy5pbmtzY2FwZS5vcmeb7jwaAAAA5ElEQVQoU23NPSgEABTA8d+xGs7glIXFRyaZlCzqysBAKYObZBe3cMrqMlkMJicZDTZlNBEpi+/hio5MFqnLs+jcV//l9d6vntAsbYrSITSexoyHoGSlOTjyoj04tdccpLw7DLZd1gHDFrQE08KsRV9aa8GSsgsjQcGHSaG/7oUhZ34U9CnKyUhWAXPmdATzXn0arewrw4GyH1c2TVmWqAIG5UKQNGPHvZCV1/kPJlzrcWLflqyMjC4lA7Wg265j54q+hVQj6LVqTc66DXmJRpD27MmjB3duQz24kazrrRZEk/7AL8OWvUHCj1eEAAAAAElFTkSuQmCC');
	}

	span#linkedin::before {
		content:  url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QAAKqNIzIAAAAJcEhZcwAADdcAAA3XAUIom3gAAAAHdElNRQfiBREQLip7h8wpAAAAq0lEQVQoz43RsUrDUBjF8R9tsgiCkNK12QxOHRyd6uqQV7jQhxDdBEcfSHBzEEneQxeHItQtt0MVg96QnjN+f8534JALGjHhRpATkscfBxpR59VmIEUU3eE0nTEBJ5gZ0J581w20EEUPKpeiWuXGWuHKYx+4RilaIpODI1+/HfpaePOMrSf4D6wULszxkgam3w/o0sAfjQKZ1rla6Ri3PpyBe5+WaA8Ya2TuHXoLfqgaNHiGAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDE4LTA1LTE3VDE2OjQ2OjQyKzAyOjAwvh4tdQAAACV0RVh0ZGF0ZTptb2RpZnkAMjAxOC0wNS0xN1QxNjo0Njo0MiswMjowMM9DlckAAAAZdEVYdFNvZnR3YXJlAHd3dy5pbmtzY2FwZS5vcmeb7jwaAAAAAElFTkSuQmCC');
	}

	.text-center {
		text-align: center;
	}

	.left-pad {
		margin-left: 10px;
	}

	.right-float {
		float: right;
	}

	@media print {
		body {
			border: 0px;
		}

		/* Prevent Python-Markdown from ruining print output */
		.markdown-body a[href]:after {
			content: "";
		}

		.print-show {
			display: block;
		}

		span#github::before {
			content: 'GitHub: ';
		}

		span#so::before {
			content: 'Stack Overflow: ';
		}

		span#linkedin::before {
			content: 'LinkedIn: ';
		}

		.print-hide {
			display: none;
		}

		.live-link {
			margin-top: 25px !important;
		}
	}
</style>

<!-- BEGIN RESUME -->
<div class="text-center">
	<h3>Matthew Miller</h3>
	<span class="phone">(951) 751-7780</span>&nbsp;&nbsp;&nbsp;&nbsp;<span class="email">matthew@millerti.me</span>
	<br>
	<span id="github"></span> <a href="https://github.com/MasterKale?tab=repositories" target="_blank">MasterKale</a>&nbsp;&nbsp;&nbsp;&nbsp;<span id="so"></span> <a href="http://stackoverflow.com/users/2133271/iamkale" target="_blank">IAmKale</a>&nbsp;&nbsp;&nbsp;&nbsp;<span id="linkedin"></span> <a href="https://www.linkedin.com/in/IAmMatthewMiller/" target="_blank">IAmMatthewMiller</a>
</div>

---------
#### Skills & Expertise

**Languages** <span class="right-float">Python, JavaScript/TypeScript, SCSS, YAML, GraphQL</span>
<br>
**Frameworks** <span class="right-float">Angular, React, VueJS, Django, Graphene, Docker</span>

---------
#### Work History

**UI Developer**, DHAP Digital, Inc. <span class="right-float">10/2016 - Present</span>

<p class="left-pad">Architect and lead development on enterprise-grade websites and single-page applications. Work directly with clients to establish and clarify business requirements, as well as coordinate development efforts between team members to ensure timely deliverables.</p>

**Full Stack Developer**, Multi Media Services <span class="right-float">05/2016 - 10/2016</span>

<p class="left-pad">Architected and produced white-label video streaming and image hosting web applications to operate at scale. Stack included Angular and Django Rest Framework, with Kubernetes and AWS for scalable hosting.</p>

**Lead Full Stack Developer**, STS Innovation, Inc. <span class="right-float">07/2014 - 05/2016</span>

<p class="left-pad">Developed and maintained a highly focused, low-cost SaaS web app for shift management using Django Rest Framework and AngularJS. Worked directly with clients to gather specifications for upcoming projects. Managed project requirements and timelines and maintained regular contact with clients. Established and managed coding and deployment standards to ensure consistency across Debian-based hosting environments. Provided Japanese/English bilingual application development support to colleagues in Japan.</p>

---------
<p class="print-show spacer">&nbsp;<br><br><br></p>
#### Projects

**Tangerine**, Banking Portal (DHAP Digital, Inc.) <span class="right-float">https://www.tangerine.ca</span>

<p class="left-pad">Helped architect and lead development of an enterprise-grade, multi-lingual AngularJS 1.5 single-page application now in production for online Canadian bank Tangerine. Created several high-level components and services, including "flow" service for declaring and orchestrating step-by-step banking-related processes. Also created sections responsible for: displaying user's list of accounts; transferring money between user's accounts; new user enrollment; and for verifying user identity via knowledge-based authentication.</p>

**Goon Discord Network**, Discord Server Directory <span class="right-float">https://goondiscordnetwork.com</span>

<p class="left-pad">Architected and maintain a Python-powered Discord bot "service" that assists with discoverability of nearly 100 affiliated Discord servers. The Django-powered homepage displays a live, searchable list of enrolled servers. The bot also handles forum membership authentication to enable server administrators to create "members only" servers. Automatic privilege elevation across enrolled servers offers streamlined UX to users joining multiple servers.</p>

**GoonAuth2**, Authentication REST API <span class="right-float">https://github.com/MasterKale/GoonAuth2</span>

<p class="left-pad">A simple Falcon- and Redis-powered REST API service that can be used to verify membership in the Something Awful internet forum.</p>

**gSho**, Japanese Dictionary for Android <span class="right-float">http://gshoapp.com</span>

<p class="left-pad">One of the first Android J/E dictionary apps to feature layouts optimized for both phones and tablets, as well as a host of other useful features. Since launch the app has maintained an average install base of over 600 users, and has grossed over $100 in IAP revenue.</p>

---------
#### Education

**University of California, Riverside** <span class="right-float">06/2011</span>

<p class="left-pad">BS in International Business and a minor in Japanese, Magna Cum Laude</p>

**International Christian University (Tokyo, Japan)** <span class="right-float">2008-2009</span>

<p class="print-show text-center live-link">See this resume live at <a href="">https://millerti.me/resume/</a></p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-75801445-2', 'auto');
  ga('send', 'pageview');
</script>
<!-- END RESUME -->