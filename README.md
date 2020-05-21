# BIT607_AS2_3406780

Guidelines and comments on choices i made
1. Changed footer column widths to percentages instead of absolute values so that each column would share equal space
2. Added a media query to support responsive design when working on a device with a max-width of 600px
3. Created a table style for the menu items to keep everything aligned in each row and column.  It also provides default settings for column headers when using <th>.
4. Created seperate column classes to define the height based on the content for each column element.
5. Set the copyright notice to <small>.
6. Used hyperlinks where possible.
7. I separated CSS for each page into separate files initially as it was easier to work with each page.  I then tidied this up and cleaned up a lot of the code by combining styles of the same class and settings into the default.css file, and referencing those in the relevant pages.  All pages shall be utilizing the same styles where relevant.
8. For font-size i have applied vw instead of actual value so that text is easily viewable when viewing from different devices.
9. Any pictures utilized have alternative text which is inline with WCAG guidelines.
10. Semantic elements have been used to mark up the structure of each web page.
11. HTML elements have been used for the page layout.

Types of Security Issues Website designers should consider:
1. Confidentiality - Ensuring information assets should only be accessed by people who are specifically allowed read access.  Hackers can steal or guess passwords and gain access to data held on a server.  
2. Integrity - Modified only by those who are specifically permitted to write.  Integrity can also be violated by hackers attempting to gain acess and modify data stored on a server.  They may also eavesdrop on communications and intercept or modify these communications.  A good example is a man-in-the-middle attack where a client believes they are talking to the server and vice-versa, but the attacker sits in the middle of communications with full control over the communications.
3. Availability - Available to specified people whenever they require access.  This can be violated when a hacker overloads a server with a large number of requests in excess of what the server has been designed to handle.  This is know as a denial of service attack (DoS)

