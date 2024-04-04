---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

Welcome!

This site attempts to contain as full a record as possible of Spencer Mowdy Hill's most important accomplishments and content. The content has been organized into several subpages.
<style type="text/css">
	.container {
		position: relative;
		overflow: hidden;
		width: 100%;
		padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
	}
	.responsive-iframe {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
		width: 100%;
		height: 100%;
	}
	.mobileShow { display: none;}
	@media only screen
	and (min-device-width : 320px)
	and (max-device-width : 480px){ .mobileShow { display: inline;}}
</style>
<div class="mobileShow">
	<ol>
	<li><A HREF="/videos/">Videos</A></li>
	<li><A HREF="/news/">In The News</A></li>
	<li><A HREF="/music/">Music</A></li>
	<li><A HREF="/code/">Coding</A></li>
	<li><A HREF="/about/">About</A></li>
	</ol>
</div>


# Spencer's Latest Youtube Video:
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="/assets/js/youtubeembed.js"></script>
<div class="container">
	<iframe class="responsive-iframe" id="youtube_video" width="600" height="340" frameborder="0" allowfullscreen></iframe>
</div>