<!--
	Rendered with MarkdownPreview in Sublime Text 3 (https://github.com/facelessuser/MarkdownPreview)
	- Command Palette > "Markdown Preview: Save to HTML" > "markdown"
-->
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

	.markdown-body .header-meta {
		list-style: none;
		margin: 0 auto;
		margin-bottom: 0.25em;
		padding-left: 0;
		display: flex;
		width: 80%;
		justify-content: center;
	}

	.markdown-body .header-meta li {
		display: inline-block;
		flex: 0 1 10em;
		margin: 0;
		padding: 0;
	}

	.markdown-body .job-description { list-style-type: '👾'; }

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

		.markdown-body .header-meta {
			width: 100%;
		}

		.markdown-body .header-meta li {
			flex: 1;
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
	<ul class="header-meta">
		<li>(951) 751-7780</li>
		<li>matthew@millerti.me</li>
		<li>Long Beach, CA</li>
	</ul>
	<ul class="header-meta">
		<li>
			<span id="github"></span>
			<a href="https://github.com/MasterKale" target="_blank">MasterKale</a>
		</li>
		<li>
			<span id="linkedin"></span>
			<a href="https://www.linkedin.com/in/IAmMatthewMiller/" target="_blank">IAmMatthewMiller</a>		
		</li>
		<li>
			<span id="so"></span>
			<a href="http://stackoverflow.com/users/2133271/iamkale" target="_blank">IAmKale</a>
		</li>
	</ul>
</div>

---------
#### Objective

On the search for opportunities to build cool things and mentor those starting out.

---------
#### Skills & Expertise

**Languages** <span class="right-float">JavaScript (ES6), TypeScript, HTML5, SCSS, Python, YAML, GraphQL</span>
<br>
**Frameworks** <span class="right-float">React, VueJS, Apollo, MobX, Webpack, Django, Docker</span>

---------
#### Work History

**Senior Full Stack Engineer**, BCG Digital Ventures <span class="right-float">11/2018 - Present</span>

<ul class="job-description">
	<li>Collaborate with corporate partners from Fortune 100 companies to architect and rapidly build out scalable web-based MVPs.</li>
	<li>Worked directly with Product and Design to define and then build out an interface for real-time configuration of a computer-vision-powered industrial safety system.</li>
	<li>Inherited and enhanced an AI event processing service to handle more than 100,000 CV events per day across 8 cameras with an average latency of 220ms</li>
</ul>

**UI Developer**, DHAP Digital, Inc. <span class="right-float">10/2016 - 11/2018</span>

<ul class="job-description">
	<li>Architected and lead development on enterprise-grade websites and single-page applications while meeting directly with clients for requirements gathering.</li>
	<li>Built out library of reusable front end components that helped skeleton crew of five developers deliver a complex mobile banking rewrite in less than 10 months.</li>
</ul>

**Full Stack Developer**, Multi Media Services <span class="right-float">05/2016 - 10/2016</span>

<ul class="job-description">
	<li>Single-handedly designed and produced the front end for white-label video streaming and image hosting web applications to operate at scale.</li>
</ul>

**Full Stack Developer**, STS Innovation, Inc. <span class="right-float">07/2014 - 05/2016</span>

---------
<p class="print-show spacer">&nbsp;<br><br><br><br></p>
#### Projects

**Goon Discord Network**, Discord Server Directory <span class="right-float">https://goondiscordnetwork.com</span>

<p class="left-pad">Created a community of 100+ SA-affiliated Discord servers to make it easy for members to find servers populated with other forum members. The accompanying Discord bot has enabled over 13,000 members to verify forum membership to receive elevated access permissions across GDN-enrolled Discord servers. This enables administrators to easily maintain "members-only" servers in which the majority of participating members are forum members.</p>

**SimpleWebAuthn** <span class="right-float">https://simplewebauthn.dev/</span>

<p class="left-pad">Authored and maintain a collection of TypeScript-first libraries for simpler WebAuthn integration in both modern browsers and Node. Enables server administrators to easily add secure "passwordless" login capabilities for cryptographic hardware-backed access control.</p>

**DV Mentors**, BCG Digital Ventures

<p class="left-pad">Participated as a mentor in an annual mentoring partnership between BCG Digital Ventures and Bright Star Schools, sponsored this year by the LA Kings. Worked with my mentee for five months to utilize DV's methodology to help them imagine, develop, and pitch their own idea to "improve your community with technology".</p>

**Public Speaking**
<p class="left-pad">Indepdently deliver technical talks at developer meetups on topics including React Hooks, GraphQL, and WebAuthn.</p>

---------
#### Favorite Games

Deus Ex 🕵️‍♂️ Titanfall 🤖 Team Fortress 2 🔥 Beat Saber ⚔️

---------
#### Education

**University of California, Riverside**, BS in Intl. Business, Magna Cum Laude<span class="right-float">06/2011</span>

**International Christian University (Tokyo, Japan)** <span class="right-float">2008-2009</span>

<p class="print-show text-center live-link">See this resume live at <a href="">https://millerti.me/resume/</a></p>
<!-- END RESUME -->
