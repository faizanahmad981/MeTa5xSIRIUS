 <!-- 
Menu Icon Container:
Moved the <div id="menu-icon-container"> to the <nav> element to keep it within the navigation context.
Ensured the icon itself has an ID for easier JavaScript manipulation.
         -->

/*  changes for header to the previous 
Preventing Text Wrapping:

Added white-space: nowrap; to the header nav #nav-links a and header nav #nav-links button styles to ensure that the text within the navigation links and the button does not wrap to the next line.
Header Alignment:

Updated header style to justify-content: space-between to ensure the logo is aligned to the left and the menu icon is aligned to the right.
Responsive Navigation Menu:

For mobile screens (@media (max-width: 768px)):
Set #menu-icon-container to display: block so it appears on mobile.
Set header nav #menu-icon to display: block to show the menu icon.
The navigation links container (header nav #nav-links) is initially set to display: none to hide it until the menu icon is clicked.
When the active class is added, header nav #nav-links.active is set to display: flex to show the menu.
Added width: max-content to #nav-links to ensure the menu width adjusts according to its content and does not stretch across the full screen.
Set the position of the menu to absolute and adjusted top and right to align it correctly when opened.

*/
