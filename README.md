### Project 9 for Treehouse FEWD Course
----

#### Web App Dashboard


##### To Run:
- Download or clone repo
- Open index.html in browser


##### Or:
- http://twoodman.github.io/th-fewd-project-9


##### Tested In:
Chrome 53 on Mac OS Sierra
Firefox 49 on Mac OS Sierra
Safari 10 on Mac OS Sierra

##### To Do:
- REMAKE MOCKUP
- MAKE PAGE RESPONSIVE
  - header with app name, notification icon badge, profile avatar, and name
  - svg icon based navigation with following links:
    - Dashboard
    - Members
    - Visits
    - Settings
    - Only have to build out dashboard PAGE
  - Main content area where specific dashboard widgets will go
  - Ensure that design responds well from 320px (mobile) to tablet and desktop screen sizes
- DEMO ALERT NOTIFICATION
  - purple bar near top of page starts with 'Alert'
  - should be visible on page load, but dismissable by pressing the X on it
  - include notification icon in header, use icon-bell.svg
- WEB TRAFFIC WIDGET
  - use chartjs.org or similar library to create line chart like one pictured in mockup
  - display # of visits along Y axis and date/time on X axis - see mockup for sample data
  - style chart to match style of dashboard
- DAILY TRAFFIC BAR CHART WIDGET
  - use chartjs.org or similar library to create bar chart like one in mockup
  - display # of visits along Y axis and day of the week along X axis
  - style chart to match style of dashboard
- MOBILE USER PIE CHART WIDGET
  - use chartjs.org or similar library to create donut chart like one in mockup
  - add legend for mobile, tablet, and desktop users
  - style chart to match style of dashboard
- SOCIAL STATS WIDGET
  - create a widget (or three separate widgets) to display social network stats for Facebook, Twitter, and Google+
  - use the provided svg icons for each of the social networks
  - style the social information to match the corresponding social network
  - style to match style of dashboard
- NEW MEMBERS WIDGET
  - create a widget that lists out members in a table
  - include avatar for each member, member name, email, and join date, make up info for email address and dates
  - style to match style of dashboard
- RECENT ACTIVITY
  - create widget to display recent activity from members
  - include following activities:
    - made a post
    - commented
    - new member signup
  - include svg icons for each type of activity
  - style to match style of dashboard
- MESSAGE USER WIDGET
  - create a widget for searching for a member and sending them a message
  - don't have to add real search functionality except if going for exceeds expectations
  - add a message textarea field that lets you add a message
  - use JS to allow you to submit the form and display a confirmation that the message was sent (won't actually submit form, just simulate)
  - use JS to display error messages if user isn't selected or message field is empty
  - style to match style of dashboard
- SETTINGS WIDGET
  - create a settings widget to display various setting options using different form elements
  - create an on/off widget for whether or not to send email notifications
  - create and on/off widget for whether or not to set profile to public or private
  - create a dropdown to select timezone
  - add save/cancel buttons (don't have to do anything functional)
  - style to match style of dashboard
- VALIDATE CODE
  - HTML
    - n/a
  - CSS
    - n/a
  - JSHint
    - n/a

##### Exceeds Expectations:
- NOTIFICATIONS
  - display at least two of them when user clicks notifications icon in header (this can be a pop up window or a drop down menu)
- TRAFFIC LINE CHART WIDGET
  - create a navigation similar to the one in the mockup to display different data when the Hourly, Daily, Weekly, and Monthly button is selected, and add functionality to those buttons so that a different chart is displayed on click
- DAILY TRAFFIC BAR CHART WIDGET
  - add at least one additional data set to the widget to create a grouped bar chart (each day should display to bars)
- MOBILE USER DONUT CHART
  - add at least one additional data category to donut chart
- SOCIAL NETWORK
  - add at least two additional social network icons and stats
- USER SEARCH
  - add 'autocomplete' feature to search box, listing names that match the search term
- STORAGE OF DATA
  - use local storage to save settings
  - when page is reloaded, settings are remembered
