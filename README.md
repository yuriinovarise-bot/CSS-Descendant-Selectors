CSS Descendant Selectors
Description

The descendant selector in CSS allows you to style elements based on their parent-child relationship. You specify the parent selector first, then a space, and then the child selector. This rule applies to all nested levels.

For example:

ul li {
	color: red;
}
ol li {
	color: green;
}


This will style <li> elements inside <ul> differently from <li> elements inside <ol>.

You can also chain multiple levels. For instance:

ul li i {
	color: red;
}


This will target <i> elements inside <li>, which are themselves inside <ul>.

Task 1

Given the following code:

<ul>
	<li>text <i>italic</i></li>
	<li>text <i>italic</i></li>
	<li>text <i>italic</i></li>
	<li>text <i>italic</i></li>
</ul>

<p>
	paragraph text <i>italic</i>
</p>
<p>
	paragraph text <i>italic</i>
</p>


Color the italic text (<i>) inside <ul> red.

Color the italic text (<i>) inside <p> green.

Task 2

Given the following code:

<p>
	paragraph text <b><i>bold italic</i></b>
</p>
<p>
	paragraph text <i>italic</i>
</p>


Color the italic text (<i>) that is inside <b> inside <p> red.
