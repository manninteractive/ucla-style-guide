# UI Components

### Grid System
This repsonsive grid was created to in order to give equal divisions across the content area throughout the site. We have created a 6, 5, and 4 column grid. This provides a variety of different options for layout and design as long as the amount of columns equals to the span of the grid. The margin is equal to 30px for each column. For mobile phones the columns will stack vertically.

This grid was generated at responsivegridsystem.com, using a margin of 3.49% which is equal to 30px, the amount of padding used for the gutters on the main content area of grad.ucla.edu. The grid is licensed under a Creative Commons Attribution 3.0 License.

### CSS

#### Sections

{% highlight css %}

/*  SECTIONS  */

.section {
	clear: both;
	padding: 0px;
	margin: 0px;
}

{% endhighlight %}

#### Columns

{% highlight css %}
/*  COLUMN SETUP  */
.col {
	display: block;
	float:left;
	margin: 1% 0 1% 3.49%;
}
.col:first-child { margin-left: 0; }
{% endhighlight %}

#### Groupings designed to be added together to create equal divisions.

{% highlight css %}
/*  GROUPING  */
.group:before,
.group:after { content:""; display:table; }
.group:after { clear:both;}
.group { zoom:1; /* For IE 6/7 */ }

/*  GRID OF SIX  */
.span_6_of_6 {
	width: 100%;
}

.span_5_of_6 {
  	width: 82.75%;
}

.span_4_of_6 {
  	width: 65.50%;
}

.span_3_of_6 {
  	width: 48.25%;
}

.span_2_of_6 {
  	width: 31.00%;
}

.span_1_of_6 {
  	width: 13.75%;
}
{% endhighlight %}
