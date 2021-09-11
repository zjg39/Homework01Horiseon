# Homework01Horiseon
Homework assignment 01 Horiseon webpage


Link to github repository: https://github.com/zjg39/HoriseonRefactor-HW01



A short description of this assignment...


This homework assignment was an exercise in refactoring a simple webpage.  Plainly stated, existing code was updated and improved to meet or exceed current standards without changing the way the the website looked or functioned. Let's get into it...

The code was littered with div elements that did nothing to offer any future programmers any ease of altering the code for better use.

To start, the segment just below the body tag was renamed <header> to better illustrate that the code inside built the top, or "header" of the webpage.  There were also links to  navigate around the page, so it only seemed apprpriate to add a child element nav to indicate that the list inside was for page naviagation.  Simple enough.

To make clearer the image that the user sees when he or she firsts loads the page, I copied the image link (which was initially just in the CSS file) and added it to the HTML text between the header and the main sections, spaced on either side for clarity and with a concise class name.

Moving on the the main section, this is where the meat of the site is held: the content for the user to read, descriptive photos, and such.  I didn't use article tags for the text, because I felt that text body wasn't long enough to justify them, and the nature of the page isn't journalistic in nature.  However, the information did seem like it was put into different "sections", hence the section tags in place for the div tags.

The last major section was encased in aside tags because the information and matching icons were, you guessed it, on the side of the page.  The information text and pictures were inside section tags to indicate their separation.

Lastly, all of the images were given descriptive and concise alt tags, should the user ever have trouble loading the page.  The copyright and "made by" texts were encased in a footer tags for obvious reasons.



