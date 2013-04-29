Responsive HTML5 structure for Global Blue

Key concept
Responsive design for 960px or above, 768px, 480px and 320px. 

Key components
1. Twitter bootstrap //Customized pack, DO NOT upgrade by yourself. 
2. jQuery.js 
3. Less.js
4. Modernizr.js
5. html5shiv.js
6. response.js

Instruction
1. HTML structure
-header
	-search form
	-top nav
	-brand
-navBar
-content
	-main
	-sidebar
-bottom
-footer

2. CSS
Twitter bootstrap 12 grid convention: all spans under class .row or .row-fluid MUST add up to 12. All Global Blue customised CSS is in base.less file. 

3. Image
Generate the maxium size (as the number shown on the images) and then responsively adjust them according to different resolutions.

4. Javascrip
Only use bootstrap library and dirty old hide/show trick to achieve everything. However, leave Javacript function structure in case needed.   
