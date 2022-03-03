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

	/*.markdown-body .job-description { list-style-type: '👾'; }*/

	/**
	 * - PNG icons from https://www.flaticon.com/packs/font-awesome (16 x 16)
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

	span#twitter::before {
		content:   url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAAAgQAAAIEBHRF40wAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAADgSURBVDiNpdMxSkNBEMbx3/P5rMRLiMTCxgPYmUJQtLBME7D1BhbeIW0g2HsFi9im8hI2FjaCCOrabGDf5rkmcWBgZ3b/38wyu9BgiBnCkj6LTCMulgVzH1qx8kInVVysbRtZ/IDvLDfFEQ4xwiQXSVvaxwle01wIwdwxwFuy3xK4ioe2cYbbFI57jxnTCi5yoEPguSRwj50C3LM4iVbwhdOCwPgvgYAn9DvgyzihXwU+cIdj1AnY4BrvHXDYTMa5FeEX7FVVVeMg5nbz2af2r6dc4xPnpQoFu5nfce3v/AOsiPNDxnx0iwAAAABJRU5ErkJggg==');
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

		span#twitter::before {
			content: 'Twitter: ';
		}

		.print-hide {
			display: none;
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
			<span id="twitter"></span>
			<a href="https://twitter.com/IAmKale" target="_blank">@IAmKale</a>
		</li>
		<li>
			<span id="linkedin"></span>
			<a href="https://www.linkedin.com/in/IAmMatthewMiller/" target="_blank">IAmMatthewMiller</a>
		</li>
	</ul>
</div>

---------
#### Objective

A full stack fan of WebAuthn; ever mindful of user privacy and the developer experience.

---------
#### Skills & Expertise

**Technologies** <span class="right-float">WebAuthn, TypeScript, Python, Docker</span>

---------
#### Work History

**Technical Leader**, Duo Security <span class="right-float">12/2020 - Present</span>

<ul class="job-description">
	<li>Lead development on Duo's Passwordless SSO experience to leverage WebAuthn for more secure customer authentication.</li>
	<li>Work across teams as Duo's WebAuthn SME to optimize WebAuthn implementations in Duo's core products.</li>
	<li>Represent Cisco at the Web Authentication Working Group and FIDO Technical Working Group to advance the cause of phish-proof user authentication.</li>
</ul>

**Senior Full Stack Engineer**, BCG Digital Ventures <span class="right-float">11/2018 - 12/2020</span>

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

---------
<p class="print-show spacer">&nbsp;<br><br><br></p>
#### Projects

**SimpleWebAuthn**, TypeScript WebAuthn Libraries <span class="right-float">https://github.com/MasterKale/SimpleWebAuthn</span>

<p class="left-pad">Authored and maintain a collection of TypeScript-first libraries for simpler WebAuthn integration in both modern browsers and Node. Enables server administrators to easily add secure "passwordless" login capabilities for cryptographic hardware-backed access control.</p>

**py_webauthn**, Python WebAuthn Library <span class="right-float">https://github.com/duo-labs/py_webauthn/</span>

<p class="left-pad">Rebuilt Duo's py_webauthn library from the ground up incorporating the latest functionality in L2 of the WebAuthn spec.</p>

**DV Mentors**, BCG Digital Ventures

<p class="left-pad">Participated as a mentor in an annual mentoring partnership between BCG Digital Ventures and Bright Star Schools, sponsored this year by the LA Kings. Worked with my mentee for five months to utilize DV's methodology to help them imagine, develop, and pitch their own idea to "improve your community with technology".</p>

**Public Speaking**

<p class="left-pad">Independently deliver technical talks at developer meetups on topics including React Hooks, GraphQL, and WebAuthn.</p>

<!-- ---------
#### Favorite Games

<span contenteditable="true">Deus Ex 🕵️‍♂️ Titanfall 🤖 Team Fortress 2 🔥 Beat Saber ⚔️</span>
-->

---------
#### Education

**University of California, Riverside**, BS in Intl. Business, Magna Cum Laude<span class="right-float">06/2011</span>

**International Christian University (Tokyo, Japan)** <span class="right-float">2008-2009</span>

<!-- END RESUME -->
