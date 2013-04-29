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
Use the maximum width (as the number shown on the images) and then responsively adjust according to different screen resolutions.

4. Javascrip
Only use bootstrap library and hide/show trick to achieve current structure. 
Javacript responding function structure is provided in case needed.   


Within the folder, there are:
1. Homepage design PDF as reference. Because all the other pages are simplified version of the Homepage in terms of structure, once the developer successfully combined the widget with the HTML structure. Other pages should become quite self-explanatory. If you have a preferred order of pages you want to work on, send me the order list, I will follow it and upload them onto github.

2. Index.html, the HTML structure, NO style-related CSS, all using Twitter bootstrap default style in order to present the layout and responsive features clearly.
Download Resize tool (http://lab.maltewassermann.com/viewport-resizer/) to check 960 or above, 768px, 480px and 320px. You can re-size the browser window to check but it might not be accurate, responsive design is not fluid design.

3. Assets folder, all the required CSS and JS libraries.
*Do not update the Twitter bootstrap library by yourself, because this is a customised version for Global blue.
*IE compatibility issues have been considered.

4. Readme.txt, short instructions of how to use the template. Detailed instructions are in the Index.html alongside every block of codes.

Instructions highlight:
1. Images: generate images according to the width shown on the placeholders. Height does not affect the layout structure, inquiry Julian for his requirement. The principle is to generate the maximum width image we need across all screen sizes and then responsively adjust them accordingly.
2. Logo and icons are using CSS sprite technique so no need to generate images for them.
2. Certain blocks of contents are integrated twice in Main content section and Sidebar section because we want them to show in different places according to screen size, using the class .mobile-switch .