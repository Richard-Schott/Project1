The following are stylistic notes and requirements for the portfolio project.
These were created at the onset, after creating the skeleton HTML, to document the process.
Additionally, these notes are reminders of work in progress, documenting bugs, and completing the portfolio project.
In essence, this documents my thoughts before and during the project.
Items will be organized thematically.

This project can easily be viewed at https://htmlpreview.github.io/?https://github.com/Richard-Schott/Project1/blob/master/index.html

Credits:
	"hexagon-2307350" by janjf93 (https://pixabay.com/en/users/janjf93-3084263/),
	shared under CC0 Creative Commons, free for commercial use and no attribution required.
	https://pixabay.com/en/hexagon-symbol-gui-internet-2307350/
	
	"Silver Macbook Beside White Ceramic Mug on Table" by rawpixel.com (https://www.pexels.com/@rawpixel),
	shared under CC0 Creative Commons, free for commercial use and no attribution required.
	https://www.pexels.com/photo/silver-macbook-beside-white-ceramic-mug-on-table-905873/
	
	LinkedIn icons are available at https://brand.linkedin.com/downloads
	
	Github icons are available at https://github.com/logos
	
Received help - suggestions:
	JenW
		1. Class element for images for either a max-width or transformations to hide and recenter parts of them.
		2. Move files to CSS folder. Done!
	Christopher
		1. Close project-highlights section.
	Henry [FEND]
		1. Bootstrap
		2. Take note of Layout Overview and the Grids page below it.
		3. A width is missing its colon.
		4. Project thumbnails overlap because they exceed 10% of the viewport.
	Me: I noticed that I was attempting to resize the containers above 700px, not the image classes!
	
FLEXWRAP is causing that odd stacking when I add it to the project container!
Adjusting image width resizes them, but text alignment needs to be fixed.

IDEA: Eliminate excess code, particularly the header. Maybe its style needs to be on the master.
IDEA: Consolidate some of the images into different breakpoints.
IDEA: Fix minor breakpoints for text.
IDEA: Stack images after 700px?
IDEA: Increase the header text size at 550px	
IDEA: create borderless <div> containers with a darker grey background.
ISSUE: Minor font-size breakpoint at 500px; the header is small at that point. Other text might be, too.	
IDEA: Although stock images don't require attribution, cite them in README.
ISSUE: EXPAND the <a> tags to the images.
ISSUE: Change the header's level to eliminate wraparound at 320px. <h3> doesn't work too well. <h2> seems okay.
IDEA: Create divs, with borders, around the project snapshot boxes. This will be nice on mobile layouts.
IDEA: border-radius on images make them seem less boring. It might not work on the trading card.
ISSUE: USE FORUMLAIC ID AND CLASS NAMES. THINK SECTION + TYPE OR CHARACTERISTIC.
ISSUE: REMOVE JS TAG AND COMMENT NOTES FROM HEAD.
ISSUE: RICHARD SCHOTT <h2> wraparound below 450px
		<h3> wraparound around 350px 

Preliminary notes:
NAME	text-align: right; within <header>?
		font #2d3c49
		sans-serif font
		
<header> has thick bottom-border using #7d97ad
	Should the header have an open source icon?

Height and angle of images should be responsive or otherwise scaled.

Viewport widths must accomodate desktop, mobile (Google Nexus 5) and tablet (iPad) resolutions.
	Google Nexus 5: 1920x1080, viewport 3, 640	360
	iPad:			2048x1536, viewport 2, 1024	768
Breakpoints should be set to max-width: 500px, something ranging 501-799 or so, then 960+?

"Featured Work" should consist of placeholder stock images and Github links
	Other projects, when applicable, should be featured
___

Placeholder images have alt attributes!
	Images and captions should be divs for placement
	HTX page, and animal trading card
Remember, image widths respond to viewport resolution when it's set. Am image set to width: 100% on 550px, for instance
	displays at 550px when that's the specified resolution.

	
Footer should have more information, e.g., name, copyright/year, a list of links to Twitter, Github, LinkedIn
	Unbulleted list items colored #7d97ad
__

Use comments to organize CSS.

__
Three rows, one for the header, the image, and other items. Is the footer a fourth?

__
Header is block level element, taking 100% width of parent container. It contains child elements, logo and text.
	Div contains image and text elements.

