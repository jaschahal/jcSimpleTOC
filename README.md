jcSimpleTOC
===========

jQuery plugin for creating Table of contents form header tags within an Element

<h2>Options</h2>
<ul>
	<li><strong>tocTitle</strong>: What should be the title of TOC container
<em>Default "Table of contents",</em></li>
	<li><strong>scrollSpeed</strong>: Make the scrolling fast or painfully slow. Its upto you
<em>Default: 1000,</em></li>
	<li><strong>itemTextLength</strong>: Plugin use H1,
<em>Default: 40,</em></li>
	<li><strong>tocDefaultHeight</strong>: Default height of TOC container
<em>Default:300,</em></li>
	<li><strong>useFancyScroll</strong>: If you don't want to use ugly scrollbars and use jScrollPane. when TOC height exceeds the <strong>tocDefaultHeight</strong> a scroll will appear, this if set to true will beautify that scroll.
<em>Default: true,</em></li>
	<li><strong>position</strong>: Where do you want to position your TOC. Supported values are
<ul>
	<li>bottomleft</li>
	<li>bottomcenter</li>
	<li>bottomright</li>
	<li>topleft</li>
	<li>topright</li>
	<li>sticky</li>
	<li>left</li>
	<li>right<em>Default:'left', </em></li>
</ul>
</li>
	<li><strong>autoMinimize</strong>: If you want to minimize the TOC container when user is not using it.
<em>Default:false</em>,</li>
	<li><strong>scrollingElement</strong>: By default html,body tags are used for universal scrolling. But this could be <strong>#ID</strong> or <strong>.class </strong>as long as there is a set <strong>height</strong> and <strong>overflow:auto</strong> set for that element, there shouldn't be any problem with scrolling bit. This setting is there to TOC sub elements. I doubt that you will ever use it though.</li>
	<li><em>Default:'html,body'</em>,</li>
	<li><strong>tagsForTOC</strong>: Program works with these tags. You can introduce others as long as you handle styles for the new tag.
<em>Default: 'h1,h2,h3,h4'</em></li>
</ul>
&nbsp;
<h2>Demo</h2>
<strong><a href="http://demopill.com/jquery-examples/toc/scroll-to-element.html">Demo 1</a> - A simple TOC positioned right on the screen</strong>

<strong><a href="http://demopill.com/jquery-examples/toc/scroll-to-element-left.html">Demo2:</a> TOC placed on the left with auto minimize enabled.</strong>

<h2>Usage Example</h2>

<code>
&lt;div class=".entry">
    &lt;h1>this is h1&lt;/h1>
    &lt;h2>this is h2&lt;/h2>
&lt;/div>
</code>

<code>
jQuery('.entry').jcSimpleTOC({
				position:'topright',
				autoMinimize:true // and other options follows
				});
</code>

For more details please visit my blog http://jaspreetchahal.org

Article is hosted here
http://jaspreetchahal.org/jquery-element-to-table-of-contents-plugin/