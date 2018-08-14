User Centric Frontend Development Milestone Project:
====================================================
The Monkees Band Site using HTML and CSS
====================================================

*by Daniel Casey*
----------------------
26 - 07 - 2018

Requirements
-------------

Using HTML and CSS skills developed during initial modules in the Code Institute Full Stack Development course, build a static website for a band.

The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.
Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
The band provided photos, video clips and audio clips to use in the website.

The band is The Monkees

Site Layout
---------------
The site has 4 pages *index.html*, *media.html*, *about.html* and *bookings.html*. A tabaular navigation bar is common through out to go between the the pages, the footer is also common and gives links to the bands social media presence.

*__index.html__* is the home page. Containing the most important information to both the user and the band - ticket sales and the hit song.

*__media.html__* provides the user with two additional songs via an audio player, with the lyrics under for their singalong pleasure.

*__about.html__* gives the user information on the bands history as well as information into the band memebers personnal lives.

*__bookings.html__* alows the user to book the band into their event.

Technolgies Used
---------------
* __Balsamic__ was used to develop wireframes for the initial design
* __Bootstrap 3.3.7__ (https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css) was used for layout styling. 
 - __Boostrap Grid__ system was used for content arrangment and responsive behavour when moving between different screen sizes
 - __Boostrap Navbar__ was used for the main navigation. Collapsible burger style menu was utilised for lower screen resolutions.
 - __Bootstrap Forms Controls__ were used for the Bookings section
 - __Bootstrap Font-Awesome 4.7.0__ (https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css) was used for the social media icons in the footer
* __Eye Dropper__ (https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka) color picker chrome extension was used to select colors from the provided videos
* __Color-Calculator__ (https://www.sessions.edu/color-calculator/) was used to play with the colors picked up using Eye Dropper. Mostly to brighten dulled colors while maintaining the pastol style of them 60's cool cats.

Testing
------------

__Code Validation__

* __HTML__ was validated using https://validator.w3.org/. No functional errors, but warnings that "The document is not mappable to XML 1.0 due to two consecutive hyphens in a comment."
* __CSS__ was validated using https://jigsaw.w3.org/css-validator/validator. No  errors were found.
* __Spelling and Grammer__ was validated using http://www.reverso.net/spell-checker/english-spelling-grammar/.

__Visual Testing__

The dev tool within Google Chrome was used to test that the pages were displaying correctly (alignment, spacing, position etc) across different screen widths.  

|               | Galaxy S5 | Pixel 2 | Pixel 2XL | iPhone 5/SE |	iPhone 6/7/8 | iPhone 6/7/8 + | iPhone X | iPad            | iPad Pro               | Responsive 1366 x 768 | Responsive 1680 x 1050 |  
| ------------- | --------- | ------- | --------- | ----------- | -------------- | -------------- | -------- | --------------- | ---------------------- | --------------------- | ---------------------- |
| index.html    | OK        | OK      | OK        | OK          | OK             | OK             | OK       | OK              | OK<sup>1.</sup>        | OK                    | OK                     | 
| media.html    | OK        | OK      | OK        | OK          | OK             | OK             | OK       | OK              | OK                     | OK                    | OK                     | 
| about.html    | OK        | OK      | OK        | OK          | OK             | OK             | OK       | OK              | OK                     | OK                    | OK                     | 
| bookings.html | OK        | OK      | OK        | OK          | OK             | OK             | OK       | OK              | OK                     | OK                    | OK                     | 
| navbar        | OK        | OK      | OK        | OK          | OK             | OK             | OK       | OK<sup>2.</sup> | OK                     | OK                    | OK                     | 

<sup><b>1.</b></sup> <i>index.html</i> looks empty when in a larger portrate view, with more contentent could make more visualy appealing.

<sup><b>2.</b></sup> The navbar display did not funtion correctly at exactly 768px (iPad resolution), and required addtional media queries to correct.

__Functional Testing__

|                | Chrome (Desktop) | Edge (Desktop) | Chrome (Mobile) | Samsung Internet (Mobile)|
| -------------  | ---------------- | -------------- | --------------- | ------------------------ |
| Ticket Links   | OK               | OK             | OK              | OK                       |
| Video Playback | OK               | OK             | OK              | OK<sup>1.</sup>          | 
| Logo Link      | OK               | OK             | OK              | OK                       |
| Heads Link     | OK               | OK             | OK              | OK                       | 
| Navbar Links   | OK               | OK             | OK              | OK                       | 
| Navbar Collapse| OK               | OK             | OK              | OK                       | 
| FB Link        | OK               | OK             | OK              | OK                       |
| Twitter Link   | OK               | OK             | OK              | OK                       |
| Instagram Link | OK               | OK             | OK              | OK                       | 
| Youtube Link   | OK               | OK             | OK              | OK                       | 
| Spotify Link   | OK               | OK             | OK              | OK                       |
| Audio 1        | OK               | OK             | OK              | OK                       |
| Audio 2        | OK               | OK             | OK              | OK                       |
| Wiki Links     | OK               | OK             | OK              | OK                       |
| Booking Form   | OK               | OK             | OK              | OK                       |
| Submit Btn     | Error<sup>2.</sup>|Error<sup>2.</sup>|Error<sup>2.</sup>|Error<sup>2.</sup>    |    

<sup><b>1.</b></sup> No audio controls on the Samsung Internet video player. Video plays in mute.

<sup><b>2.</b></sup> Correctly asks to enter data before executing. <i>405 Not Allowed</i> error once executed, expected as form not yet linked to database.


Monkees are Live!!
---------------------

The site was published via GitHub hosting and can be accessed at https://dcasey720.github.io/band-site/