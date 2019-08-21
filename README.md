# Responsive-Web-Design
Responsive Web Design with Optimized Print Page Setup

HTML Codes for Webpage
<!DOCTYPE HTML>
<html>

<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Creating a Responsive Web Design</title>
	
	<!-- Link for sheet styling -->
	<link rel="stylesheet" type="text/css" media="screen" href="css/screen.css">
	
	<!-- Link for print styling, page styling changes 
		when ready to  print webpage -->
	<link rel="stylesheet" type="text/css" media="print" href="css/print.css">
	
</head>

<body>
	<div id="page">
		<header>
			<a class="logo" title="Everyday Things" href="http://codifydesign.com">
				<span>Everyday Things</span></a>
			<div class="hero">
				<h1>Add interest with natural textures</h1>
				<a class="btn" title="Get advice from top designers" href="#">
					Get advice<span> from top designers</span></a>
			</div>
		</header>

		
		<section class="main">
			<aside>
				<div class="content trending">
					<h3><a href="#">What&apos;s trending</a></h3>
					<p>Lorem ipsum dolor sit amet, consect etuer adipiscing elit. 
					<a href="http://codifydesign.com">Morbi commodo</a>, 
						ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio 
						lorem non turpis.</p>
				</div>
			</aside>
				
			
			<aside>
				<div class="content find-it">
					<h3><a href="#">Where to find it</a></h3>
					<p>Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, 
						id pulvinar odio lorem non turpis. Nullam sit amet enim. Lorem ipsum 
						dolor sit amet, consect.</p>	
				</div>
			</aside>
			
			
			<aside>
				<div class="content tools">
					<h3><a href="#">Tools of the trade</a></h3>
					<p>Nullam sit amet enim. Lorem ipsum dolor sit amet, consect etuer 
						adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci 
						rhoncus neque, id pulvinar odio.</p>
				</div>
			</aside>
		</section>

		
		<section class="atmosphere">
			<article>
				<h2>Creating a modern atmosphere</h2>
				<p>Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id 
					pulvinar odio lorem non turpis. Lorem ipsum dolor sit amet etuer 
					adipiscing elit.  Pulvinar odio lorem non turpis. Nullam sit amet enim 
					lorem.</p>
				<a class="btn" title="Creating a modern atmosphere" href="#">Learn more</a>	
			</article>
		</section>
		
		
		<section class="how-to">
			<aside>
				<div class="content">
					<img alt="Choosing the proper seating" src="images/photo_seating.jpg">
					<h4>How-To: Seating</h4>
					<p>Consectetuer adipiscing elit. Morbi commodo ipsum sed gravida orci 
						magna rhoncus pulvinar odio lorem.</p>
					<a title="Learn how to choose the proper seating." 
					href="http://codifydesign.com">Learn more</a>
					</div>
			</aside>

			
			<aside>
				<div class="content">
					<img alt="Choosing the proper lighting" src="images/photo_lighting.jpg">
					<h4>How-To: Lighting</h4>
					<p>Morbi commodo, ipsum sed pharetra gravida magna rhoncus neque id 
						pulvinar odio lorem non turpis nullam sit amet.</p>
					<a title="Learn how to choose the proper lighting." 
					href="http://codifydesign.com">Learn more</a>
				</div>
			</aside>


			<blockquote>
				<p class="quote">Lorem ipsum dolor sit amet conse ctetuer adipiscing elit. 
					Morbi comod sed dolor sit amet consect adipiscing elit.</p>
				<p class="credit"> <strong>Author Name</strong><br> 
					<em>Business Title</em><br> Company</p>
		
			</blockquote>
		</section>
	
		
		<nav>
			<ul>
				<li>
					Touch enable for sub-menus on touch devices 
					<a title="About Us" href="#"
						aria-haspopup="true">About Us</a>
					<ul>
						<li>
							<a title="Sub Link 1" href="#">Sub Link 1</a>
						</li>

						<li>
							<a title="Sub Link 2" href="#">Sub Link 2</a>
						</li>
					</ul>
				</li>

				<li>
					<!-- Touch enable for sub-menus on touch devices -->
					<a title="Design Corner" href="#"
					aria-haspopup="true">Design Corner</a>
					<ul>
						<li>
							<a title="Sub Link 1" href="#">Sub Link 1</a>
						</li>

						<li>
							<a title="Sub Link 2" href="#">Sub Link 2</a>
						</li>


						<li>
							<!-- Touch enable for sub-menus on touch devices -->  
							<a title="Sub Link 3" href="#"
							aria-haspopup="true">Sub Link 3</a>
							<ul>
								<li>
									<a title="Sub Sub Link 1" href="#">Sub Sub Link 1</a>
								</li>

								<li>
									<a title="Sub Sub Link 2" href="#">Sub Sub Link 2</a>
								</li>
							</ul>
						</li>

					</ul>
				</li>


				<li>
					<a title="Products" href="#" 
					aria-haspopup="true">Products</a>
					<ul>
						<li>
							<a title="Sub Link 1" href="#">Sub Link 1</a>
						</li>

						<li>
							<a title="Sub Link 2" href="#">Sub Link 2</a>
						</li>
					</ul>
				</li>


				<li>
					<a title="Contact Us" href="#">Contact Us</a>
				</li>
			</ul>
		</nav>
	

		<footer>
			&copy; Everyday Things
			<div class="content">
				<a title="Privacy Policy" href="#">Privacy Policy</a>
				<a title="Terms of Service" href="#">Terms of Service</a>
			</div>
		</footer>

	</div>
</body>

</html>




CSS Styling Codes for Webpage
/* CSS Document for Screens */
/* This part of the project handles the dynamics of the webpage using CSS.
This means, the webpage is responsed, adjusted to different pixel density */

/*The font used in this website is Google fonts, Open Sans. Used for the
entire body of the site. The selection of Open Sans are the following:
1) light 300
2) light 300 italic
3) bold 700
4) bold 700 italic. */
@import url('https://fonts.googleapis.com/css?family=Open+Sans:300,300i,700,700i&display=swap');


/* Applying styling to the body */
body {
    font-family: 'Open Sans', sans-serif; font-size: 16px; font-weight: 300;
    color: #555; margin: 0; padding: 0;
}


/* This limits the width of all items in the body 
all items are position relatively, page are extended
auto is used to center all content of the page*/
#page { max-width: 1200px; margin: 0 auto; position: relative;}


/* Styling applying to text
The number systems used in CCS Ex: 0     0      0        0 
                                   Top   Right  Bottom   Left
These are the styling for h1, h2, h3, and h4*/
h1 { margin: 0 0 1em 0; font-size: 2.8em; font-weight: 700;}
h2 { margin: 0 0 .5em 0; font-size: 1.6em; font-weight: 700; line-height: 1.1em;}
h3 { margin: 0 0 .5em 0; font-size: 1.3em; font-weight: 700;}
h4 { margin: 0 0 1.5em 0; font-size: 1em; font-weight: 700;}


/* Styling for the paragraph */
p { margin: 0 0 1em 0;}


/* Styling applied to anchor tag 00 for red, 7e for green, and ff for blue */
a { color: #007eff;}


/* Text color when the link has been visited. Lighter color of non-visited anchor 
#65 for red, b1 for green, and ff for blue*/
a:visited { color: #65b1ff;}

a.btn {font-size: 1.2em; 
    /* Anchor lnk with class of button will not be underlined */
    text-decoration: none; color: #fff; 
    /* border properties: width, style, and color */
    border: 1px solid #fff; 
    /* Padding controls space inside element, need not border to touch text */
    padding: /* Top&Bottom */ 4px /* Left&Right */ 15px;
    /* Transition to background with 0.5 second duration */
    transition: background-color 0.5s;
}
/* Hover state for the button class */
a.btn:hover { /* Defined color of background color using rgba 
    (a is alpha) which defines level of transparancy */
    background-color: rgba(0, 0, 0, .3);
}

/* Styling for the header */
header { height: 430px; background: #cf0004 url(../images/banner_1200.jpg)
no-repeat /* The center and bottom are defined for X&Y Coordinates*/center bottom; 
/*Any items is position to the header itself as defined by position: relative */
position: relative;}


/* Header with a class logo
HTML anchor tag that contain the logo class */
header a.logo{
    /* A Z-INDEX allows to re-arrange and re-stack element,
    this changing the order of things making it the top
    element. However, all z-index has a 0 default value. */
    z-index: 1;
    /* Position absolute does not affect position relative
    items display on webpage are position according to position relative only 
    and anchor tag does not have dimensions so display in blocks turns into 
    a block object */
    position: absolute;
    display: block; width: 160px; height: 66px;
    background: url(../images/logo.svg) no-repeat
    /* X&Y coordinate 0, 0 */
    0 0; 
    /* Background graphics fit to page width */ background-size: contain; 
    top: 15px; left: 20px;
}
/* Span to hide link title from everyday things logo. 
logo is to navigate in place of Link, just not showing */
header a.logo span { display: none;}

header div.hero {position: absolute; width: 42%; top: 30px; left: 55%;}
header div.hero h1 {line-height: 1em; margin: 0 0 30px 0; color: #fff;}


/* Properties used for all sections */
section { padding: 0 30px; }

/* Defining pseudo element, either one colon (:) or two colons (::) 
are used to visually represent a pseudo elelment property versus 
pseudo class */
section::after { content: ''; display: block; clear: both;}


/* Properties used only for main sections */
/* This section alson create the colums for the section aside */
section.main { margin-top: 20px; margin-bottom: 30px; padding: 0; }
section.main aside { width: 33%; float: left; text-align: center;}

/* Styling the content inside each aside section */
section.main .content { margin: 15px; background: no-repeat center top;
    background-size: 75px 75px; padding-top: 85px;
}

/* Styling for headings inside each aside section */
/* Changing the color of each link item */
section.main aside h3 a { color: #000; text-decoration: none;}
/* Adding underline when hover over link items */
section.main aside h3 a:hover { text-decoration: underline;}

/* These will target styling individually to each item under specifically
defined aside classes */
/* This element target both classes .content and .trending */
/* SVG --> Scalable Vector Graphics which can be scaled to any
size within the browser */
section.main aside .content.trending {
    background-image: url(../images/icon_star.svg); 
}
section.main aside .content.find-it {
    background-image: url(../images/icon_marker.svg); 
}
section.main aside .content.tools {
    background-image: url(../images/icon_gear.svg); 
}


/* Styling for atmosphere section */
section.atmosphere { background-color: #cc6633; padding-top: 30px;
    padding-bottom: 30px; color: #fff;
}
/* Background image for atmosphere section which contains the article element */
section.atmosphere article { padding: 0 20px 0 515px; 
    background: url(../images/photo_lounge.jpg) no-repeat 0 5px;
    /* Minimum height so that the background isn't cut-off because of minimal
    content from article section and will not be shorter than the
    defined pixels */
    min-height: 220px;
}


/* Styling for How to section */
section.how-to { background-color: #eee9d9; position: relative; }
section.how-to aside { width: 30%; float: left; margin-right: 10px; }
section.how-to aside .content { padding: 30px 30px 20px 0; }
section.how-to aside .content img { display: block; margin-bottom: 15px;
    width: 70%;
}

/*Styling for text of how to section */
section.how-to aside .content h4 { margin-bottom: 0; }
section.how-to aside .content p { margin-bottom: .5em; }
section.how-to aside .content a { display: inline-block;
    color: #cc6633; font-weight: 700;
}


/* Styling for block quote */
section.how-to blockquote { 
    margin: 0;  width: 32%;
    color: #444;
    background-color: #fff;
    position: absolute; bottom: 0; right: 4%;
}

section.how-to blockquote p { margin: 30px 30px 20px 50px; }
section.how-to blockquote p.quote { font-style: italic; font-size: 1.2em; }
section.how-to blockquote p.credit { 
    color: #777;
    font-size: .9em; margin-top: 0; padding-left: 20px; line-height: 1.3em;
    position: relative; 
}

/* Pseudo element for blockquote */
/* Left quote for top of quote section */
section.how-to blockquote::before {
    content: '\201c'; color: #d2bd65;
    position: absolute;
    top: 10px; left: 8px;
    font-size: 5em;
    font-family: serif;
}
/* Right quote for bottom quote section */
section.how-to blockquote p.quote::after { content:'\201d'; font-family: serif; }

/* Dash (-) for Em-dash in author's name section */
section.how-to blockquote p.credit::before { content: '\2014';
    position: absolute; top: -1px; left: 0;
}


/* This section styling focus on the navigation elements,
essentially creating a navigation menu using CSS */
nav { 
    background-color: rgba(0, 0, 0, .65);
    position: absolute;
    /* Navigation element set in relation to the page.
    Also set to the very top of the heading area */
    top: 0px; left: 0px;
    padding: 50px 0 0 0;
    width: 100%;
}

/* Adding pseudo element to clear out the float to make 
sure the navigation element to be high enough to
compensate the top level of the children element */
nav::after { content:''; display: block; clear: both;}


/* List item change color on hover */
nav ul li:hover { background-color: #2b0306;}
nav ul li:hover > ul { display: block;}
/* Getting rid of the bollets from the HMTL code */
nav ul { list-style: none; margin: 0; padding: 0;}

nav ul li a {
    /* Styling anchored to display more like graphics
    using the inline-block */
    display: inline-block;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    width: 120px;
    position: relative; 
}

/* Visited link color: Navigation to stay as white */
nav ul li a:visited { color: #fff;}
/* Color change for the anchor tags */
nav ul li a:hover { background-color: #6d0911;}

/* Hiding sub menu, and show only when hover over the list
items */
nav ul ul { position: absolute; top: 100%; 
    background-color: #2b0306; display: none;            
}
nav ul ul li { position: relative;}
nav ul ul ul {left: 100%; top: 0px;}

/* CSS rule to target only the top level elements */
/* Only target an unordered list if it is an immediate
the child of a navigation element */
nav > ul { padding-left: 200px;}

/* Making items flow horizontally.
List item of direct child or ul and nav */
nav > ul > li { float: left;}

/* Set up anchor link so not all is set to 100px at the 
top level */
nav > ul > li > a { width: auto; padding: 10px 20px 15px 20px;}

/* Can't target parent tag if only a particular child, aply fix
using added Aria tag... Styling display indication arrows 
for items with sub-menus... Target any element with the defined
attribute. For each one found, create triangle with using CSS */
nav a[ aria-haspopup="true"]::after {
    content: '';
    display: block; width: 0px; height: 0px;
    position: absolute;
    top: 16px; right: 15px;
    /* Displaying the triangle */
    border-top: 4px solid transparent;
    border-bottom: 4px solid transparent;
    border-left: 4px solid #fff;
}

/* Having arrows orientation pointing downwards instead of rightward */
nav > ul > li > a[ aria-haspopup="true"]::after {
    border-left: 4px solid transparent;
    border-right: 4px solid transparent;
    border-top: 4px solid #fff;
    left: 20px; right: auto;
    bottom: 6px; top: auto;
}


/* Styling for the footer section */
footer { font-size: .8em; margin: 40px; color: #999;
}

/* Setting display type of inlie, which is the default
for anchor link and span element. Allows that element to 
flow alongside other content so the hyperlink won't show
up on a separate line from the copy right because the div
element has block properties but rather the anchor link 
inside of that div element will flow or align next to
our copy right element.. */
footer .content { display: inline; }

/* Anchor link inside the footer */
footer a { margin-left: 30px; color: #777;}
/* Color won't change when someone visited the links
with assigned pseudo class (visited) */
footer a:visited { color: #777}
/* Color change when hover over element */
footer a:hover { color: #000;}



/* Media queries: Adjustments for large or medium size screen variations */
@media screen and (max-width: 1000px){
/* Any rules defined in this section will take effect when screen
sizes are at the defined value or less, else they are simply ignored */
h1 { font-size: 2.4em;}

/* Header */
header div.hero { left: 56%;}
header div.hero h1 { margin-bottom: 20px;}

/* Section - Atmosphere */
section.atmosphere article { padding-left: 400px;
    background-size: 375px auto;}
}



/* Media queries: Adjustments for medium size screen variations */
@media screen and (max-width: 825px) {
/* Any rules defined in this section will take effect when screen
sizes are at the defined value or less and a new image graphic is 
imported, else they are simply ignored */
h1 { font-size: 2.2em;}

/* Header */
header { height: 300px; background-image: url(../images/banner_825.jpg);}
header div.hero { top: 120px; left: 48%;}

/* Section - Atmosphere */
section.atmosphere article { padding-left: 325px;
    background-size: 300px auto;}

/* Section - How To */
section.how-to blockquote p.quote { font-size: 1.1em; line-height: 1.2em;}
section.how-to blockquote p.credit { font-size: .85em;}
}



/* Media queries: Adjustments for medium size screen variations */
@media screen and (max-width: 760px) {
    /* Any rules defined in this section will take effect when screen
    sizes are at the defined value or less and changes size of image 
    graphic, else they are simply ignored */
    h1 { font-size: 1.8em;}
    h2 { font-size: 1.4em;}
    h3 { font-size: 1.1em;}
    a.btn { font-size: 1em;}

    /* Header */
    header a.logo {width: 145px; height: 60px;}
    header div.here { top: 140px; left: 48%;}

    /* Section - Main */
    section.main { margin-top: 10px; margin-bottom: 10px;}
    section.main aside div.content { 
        background-size: 55px 55px; padding-top: 60px;
    }

    /* Section - How To */
    section.how-to aside div.content img { width: 85%;}

    /* Navigation */
    nav { padding-top: 80px;}
    nav > ul { padding-left: 10px;}
}



/* This portion of the project handles adjustments for small screens */
@media screen and (max-width: 625px) {
    /* Any rules defined in this section will take effect when screen sizes
    are the defined value or less. Replaced the graphic */
    h1 { font-size: 1em;}
    h3 { margin-bottom: 0px;}
    a.btn { font-size: .9em;}

    /* Header */
    header { height: 160px; background-image: url(../images/banner_625.jpg);
        /* Define the background position of the image at the top left
        section of the page */
        background-position: left top;
    }
    /* Creating the effect of overhead drop provided by navigation menu when
    move to the bottom of when on smaller screen sizes */
    header a.logo {
        width: 100%; height: 66px;
        left: 0px; top: 0px;
        background-color: rgba(0, 0, 0, .65);
        background-size: 112 px 46px;
        background-position: 20px center;
    }
    /* Setting background image position to the left allows us to define pixel
    values because of defined position */
    header div.hero { width: 300px; top: 85px; left: 130px; }
    header div.hero h1 { margin-bottom: 10px; }

    /* Navigation */
    nav { position: static; width: auto; padding: 20px 15px;
    background-color: #4b0a0c;
    }
    /* Re-arranging navigation menu */
    /* Changing display format and position */
    nav ul,
    nav ul ul,
    nav ul ul ul { display: block; position: static;}

    nav > ul { padding: 0; }
    nav > ul > li { float: none; margin-top: 25px; }

    /* Removing hover state and re-styling the anchor links */
    nav ul li:hover { background: none; }
    nav ul li a {
        width: auto;
        display: block;
        margin: 8px 10px;
        padding: 8px 15px;
        border: 1px solid rgba(255, 255, 255, .25);
    }
    nav ul li a:hover { background-color: rgba(255, 255, 255, .2)}

    nav ul ul { background: none;}
    nav ul ul li a{ margin-left: 30px; }
    nav ul ul ul li a{ margin-left: 60px; }

    nav a[aria-haspopup="true"]::after { display: none;}

    /* Re-arranging footer elements */
    footer div.content { display: block; margin-top: 15px;}
    footer div.content a{ margin: 0 20px 0 0; }

    /* Re-arranging the aside and atmospher section for easier read */
    /* Section - Main */
    section.main aside { width: 100%; float: none;   text-align: left; }
    section.main aside div.content {
        margin: 8px 20px 8px 0px;
        padding: 5px 0px 10px 85px;
        background-size: 50px 50px;
        background-position: 20px 5px;
    }
    /* Displaying text beneath image in atmosphere secton */
    /* Section - Atmosphere */
    section.atmosphere article { padding: 160px 20px 0px 0px;
        background-size: 300px auto; min-height: initial;
    }
    /* Re-arranging content inside section How-To */
    /* Section - How-To */
    section.how-to aside { width: 100%; float: none; margin: 0; position: relative; }
    section.how-to aside div.content { padding: 20px 20px 20px 150px; }
    section.how-to aside div.content p { font-size: .9em; }
    section.how-to aside div.content img {
        display: inline-block;
        width: 125px;
        position: absolute;
        top: 30px; left: 0px;
    }
    
    /* Re-arranging blockquote */
    section.how-to blockquote {
        margin: 0 20px 0 40px;
        width: 90%;
        padding: 1px 0px 20px 0px;
        position: relative;
    }

}



/* This portion of the project handles adjustments for the smallest screens */
@media screen and (max-width: 425px) {
/* Any rules defined in this section will take effect when screen sizes
are the defined value or less. Replaced the graphic and the logo */
    /* header */
    header { height: 110px; background-image: url(../images/banner_425.jpg); }
    header a.logo{
        height: 36px; background: rgba(0, 0, 0, .65) url(../images/logo_small.svg)
        /*Position X and Y are set to center */
        no-repeat center center;

        /* Changing background size for the new graphics */
        background-size: 126px 17px;
    }
    header div.hero { width: 100%; left: 0px; top: 46px;    text-align: center;}
    header div.hero h1 { font-size: 1em; margin-bottom: 10px;}
    header div.hero a.btn { padding: 2px 30px; font-size: .8em; }

    /* Change the size of top button and displayed content */
    header div.hero a.btn span { display: none;}


    /* Re-styling the How To section for smallest screen */
    /* Section - How To */
    section.how-to aside div.content { padding: 140px 20px 20px 0px; }
    section.how-to aside div.content img { width: auto; height: 100px; top: 30px;}
    section.how-to blockquote { margin: 10px 40px 0px 20px; }

    
    /* Re-styling the footer for smallest screen */
    footer::after { content: ''; display: block; clear: both;}
    footer div.content a {
        display: inline-block; margin: 0 0 10px 0;
        float: left;
        clear: both;
    }
}  





Print Setup Codes: Optimized Webpage for Print Jobs
/* CSS Document for Print */

/* Imported Google font */
@import url(http://fonts.googleapis.com/css?family=Open+Sans:300italic,700italic,700,300);

/* Always accommodate margin for browser */
@page { margin: .5cm; }


/* Rule to defining properties for entire document */
body {
    color: #000;
    font-family: Georgia, 'Times New Roman', Times, serif; font-size: 12pt;
    font-weight: normal; margin: 0; padding: 0;
}



/* Properties for heads and paragraphs */
h1, h2, h3, h4 { margin: 0; font-family: "Open Sans", sans-serif; }

h1 { font-size: 1.4em; }
h2 { font-size: 1.3em; }
h3 { font-size: 1.2em; }
h4 { font-size: 1.1em; }

p { margin: 0 0 1em 0; font-size: .9em; }



/* Changing color of anchor tags and set to inherit to mimic the
body color and eliminate underline use no text decorations */
a, a:visited { color: inherit; text-decoration: none; }

/* Displaying url of link on printed page for regular and visited lniks */
a::after, a:visited ::after {
/* attr --> attributes of href being placed inside parantheses */
    content: '(' attr(href) ')';
    font-style: italic;
    /* Keeps long url from wrapping into other texts */
    word-wrap: break-word;
}

/* Eliminate navigation buttons */
nav { display: none; }



/* Styling for the headings and graphics for print page */
header { position: relative; }
header::after { content: url(../images/banner_1300_print.jpg); width: 90%; }

/* Logo position to overlap with print graphic */
header a.logo { display: block; width: 145px; height: 60px;
    position: absolute; top: 20px; left: 20px;
}

/* Image for logo header and hide the link text */
/* Displaying link for header logo */
header a.logo::before { content: url(../images/logo_print.svg); }
/* Positioning url for logo */
header a.logo::after { display: block; position: absolute; 
    top: 20px; left: 175px;
}
header a.logo span { display: none; }
header div.hero { width: 75%; position: absolute; top: 110px; left: 20px; }
/* Displaying div element url in it own line */
header div.hero a::after { display: block; }



/* Styling for all section */
section { margin: 50px; }
section::after { content: ''; display: block; clear: both;}

/* Styling for main and aside section */
section.main { margin-top: 20px; margin-bottom: 30px; }
section.main aside { width: 33%; float: left; text-align: center; }
section.main aside div.content { margin: 15px; }

/* Displaying url link plain and under the header in section headers, 
showing on its own lines */
section.main aside div.content h3 a::after { display: block;
    font-family: serif; font-weight: normal;
}
/* Svg graphics of aside main section for trending, find-it and tools */
section.main aside div.content.trending::before {
    content: url(../images/icon_star_print.svg);
}
section.main aside div.content.find-it::before {
    content: url(../images/icon_marker_print.svg);
}
section.main aside div.content.tools::before {
    content: url(../images/icon_gear_print.svg);
}



/* Styling for atmosphere section with graphics */
section.atmosphere { position: relative; margin-bottom: 40px;
    padding-top: 50px; border-top: 1px solid #ccc;
}
section.atmosphere::before { 
    content: url(../images/photo_lounge_print.jpg);
}
section.atmosphere article { width: 40%; position: absolute; 
    top: 40px; left: 425px;
}



/* Styling for How To section */
section.how-to { padding-top: 50px; border-top: 1px solid #ccc; 
    /* Allow elements from similar category to print within the same block
    using CSS page break capabilities */
    page-break-inside: avoid;
}
section.how-to aside { width: 25%; float: left; margin: 0 35px 0 0 ; }
/* Turning off the current color image, replace with new print image */
section.how-to div.content img { display: none; }

/* Injecting printing graphics using nth child technic targetting
elements of non-differentiable class from HTML page with aside section */
section.how-to aside:nth-child(1) div.content::before{
    content: url(../images/photo_seating_print.jpg);
}
section.how-to aside:nth-child(2) div.content::before {
    content: url(../images/photo_lighting_print.jpg);
}



/* Styling for blockquote within How To section */
section.how-to blockquote {
    width: 30%;
    float: left;
    margin-left: 30px;
    position: relative;
}
section.how-to blockquote::before {
    content: '\201c';
    color: #ccc;
    font-size: 5em;
    font-family: serif;
    display: inline-block;
    position: absolute; top: -20px; left: -45px;
}
section.how-to blockquote p.quote {
    font-style: italic; font-size: 1.4em; color: #888;
}
section.how-to blockquote p.quote::after {
    content: '\201d'; font-family: serif;
}
section.how-to blockquote p.credit{
    padding-left: 20px; position: relative;
}
section.how-to blockquote p.credit::before {
    content: '\2014'; position: absolute; left: opx; top: -1px;
}



/* Styling for the footer section wth graphics */
footer { border-top: 1px solid #ccc; position: relative;
    min-height: 200px; padding: 20px 0 0 170px;
}
footer::after { content: url(../images/qr_codifydesign.png); 
    position: absolute; top: 20px;  left: 0px;
}
/* Stacking anchor elements within footer section, displaying on separate lines */
footer a { display: block; margin-top: 15px; }
footer a::after { display: block; }
footer div.content { padding-left: 20px; }

/* Note for user of webpage printing origin */
footer div.content::after {
    content: 'This page was printed from http://codifydesign.com';
    display: block; margin-top: 30px; font-style: italic; font-size: .9em;
}
