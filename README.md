# Countdown-Ticker

This project creates a dynamic, real-time countdown clock using HTML, CSS, and JavaScript. It displays the number of days, hours, minutes, and seconds remaining until a specified future date. The clock updates every second to reflect the remaining time accurately. This is useful for counting down to events, launches, or deadlines.

How the Project Works:

HTML Structure (index.html)
• The HTML file sets up the structure of the countdown clock.
• It includes a div with the id clockdiv containing four sections for days, hours, minutes, and seconds.
• Each section has a span to display the numerical value and a div with the class smalltext to label the units (e.g., "Days", "Hours").


Styling (style.css)
• The CSS file styles the countdown clock.
• The body is centered, uses a sans-serif font, and has a bold style.
• The h1 tag is styled with a specific color, font size, and margin.
• The #clockdiv and its child div elements are styled to have padding, background color, and rounded corners.
• The span elements inside the #clockdiv are styled for padding and background color.


JavaScript Logic (app.js)
• getTimeRemaining(endtime) Function:
  • Calculates the time difference between the current time and the target       end time.
  • Converts this difference into days, hours, minutes, and seconds.
  • Returns an object containing these time units and the total remaining        time in milliseconds.


Initialization:
  • A target date (deadline) is set to 7 days from the current date.
  • The initializeClock function is called with the id of the clock div and      the target date to start the countdown.


How to Use:
1. Open index.html in your web browser to view the countdown clock.
2. The clock will display the remaining days, hours, minutes, and seconds       until the target date.
3. The clock updates every second to show the latest time remaining.


Author: Nilesh Parmar • Email: parmar.nil@northeastern.edu • LinkedIn: LinkedIn/Nilesh • GitHub: https://github.com/nileshparmar0
