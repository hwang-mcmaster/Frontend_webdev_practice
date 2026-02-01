Application Description
The application simply allows a user to:
1. Upload photos related to landmarks
2. Assign each photo to a geographic location on a map
3. Enter descriptive information about each landmark
4. View landmarks as markers on a Google Map
5. Click a marker to view the landmark’s information and photo(s)
All data exists only in the browser while the page is open.


Detailed Features:
A. Photo Upload & Client-Side Storage (Critical)
• Users must be able to select image files from their device
• Images must be stored using JavaScript in memory (i.e. no server upload)
B. Landmark Data Entry (Critical)
Users must be able to create landmarks by providing the following information:
• A title or name
• A short description (1–3 sentences)
• An associated image
This information must be stored in JavaScript and used to populate the UI.
C. Location Assignment (Critical)
• Each landmark must be assigned a location, allow the user to choose between the
following options to provide the location:
o Using browser geolocation
o Entering coordinates programmatically
• Location data must be clearly tied to the landmark’s information
D. Interactive Google Map (Critical)
• A Google Map must always be displayed, and should be the main focus of the
application
• Each entered landmark must appear as a marker on the map
• Clicking a marker must display:
o Landmark title
o Description
o Associated image(s)
E. DOM Manipulation & JavaScript Events (Critical)
JavaScript must be used to:
• Dynamically create, update, and remove DOM elements
• Respond to user interactions (clicks, submissions, map events)
• Update the UI without reloading the page
F. Required Additional Features 
• Show / hide individual landmarks 
• Delete a landmark and its marker 
• Edit landmark information after creation 
• Use browser geolocation to set the initial map view 
• Basic form validation with user-friendly feedback
G. Responsive Design Requirements
Your application must meet all of the following:
• Layout adapts cleanly to desktop, tablet, and mobile screen sizes
• On small screens:
o The map and content stack vertically
o Text and buttons remain readable and usable
• Images scale proportionally and never overflow their containers
• Interactive elements are large enough for touch input
• No horizontal scrolling is required at any screen size
H. Purpose & User Experience
• The application must clearly communicate its walking tour purpose
• Content must be appropriate and coherent (not placeholder text only)
• The intended user (tourist, student, local resident, etc.) should be obvious