# Week 8 (21st August - 25th August, 2023)

<h4>Last Week plans- </h4>https://github.com/israralam145/366pi-Internship-Journal/blob/main/Week%208.md.

<h4>Task- new UI of betterplanettogether.org.</h4>

Github link - https://github.com/israralam145/betterplanettogether

Figma Link- https://www.figma.com/file/JyJ46hm1zZPsldpLTJN6Gm/FloCard(Web)-Updates-V1?node-id=780%3A1208&mode=dev

# Friday, 25th August
<h3>Plan</h3>

* Adding hover element to the accordion. So that when the button reveals the content when the mouse is hovered over the button.
<h3>Progress</h3>

* Added the hover to the buttons.
* But there was a issue. When i hover over the buttons nothing happened. but once button clicked then the hover works which makes no sense.
* I've tried various methods and then noticed there is a problem in the css or theme file which conflicts the behaviour.
* I inspected the code in the browser and then i figured out when button is clicked then "show" class added. So i hardcoded the show class which solves the problem.
* Disabled the buttons in desktop view for proper working of hover since there is no need of clickable buttons in desktop view.
* Looks like the task is finished as I showed my work to Kailash Sir and he said there is no such addon needed yet.

# Thursday, 24th August
<h3>Plan</h3>

* Add accordion to the Collaboration section.
<h3>Progress</h3>

* Added accordion with the button.
* Added styling to accordion header so that it matches the design and not look like a standard accordion.
* Accordion body contains the text.

# Wednesday, 23rd August
<h3>Plan</h3>

* Working on the twitter hashtag embedding.
* Check whether there is any UI inconsistency or bug. 
<h3>Progress</h3>

* Twitter Hashtag timeline embedded. I used a website called [SocialableKIT](https://www.sociablekit.com/) which is a service allows to embed social media feeds in websites.
* I did few steps to make it work:
  1.   Logged in with Google.
  2.   Then click on "Create Widget" button on the top right corner.
  3.   Now, there is a dropdown to select the widget type. Select "Twitter Hashtag Feed" then new textbox appears asking the hashtag name. Type the hashtag name (#betterplanettogether). Click on "Next".
  4.   A page opens Customize Twitter Hashtag Feed as the name suggests which allows to change the theme, layouts, post limits, color, fonts, etc.
  5.   At last, Click on "Embed on Website". Then there will be lot of options like website, squarespace, wix, wordpress. We will choose "Website". Copy the javascript code and paste in the HTML document.

* The feed goes outside the container. To fix that I added the "overflow: auto;" style to the container elements containing the Twitter timelines.

# Tuesday, 22nd August
<h3>Plan</h3>

* Working on the responsiveness of the site.
* Adding some small UI elements.
<h3>Progress</h3>

* I'm having issues embedding twitter hashtag because twitter doesn't allow hashtag timeline. It only shows button. 

# Monday, 21st August
<h3>Plan</h3>

* Working on the new UI of [Know the SDGs](https://betterplanettogether.org/KnowSDGs#) page.
<h3>Progress</h3>

* contents have been added and hover elements are added where when the mouse hovers over the SDG images, a preview will be shown in a different container with text.
* Added required padding and alignments to look the UI more appealing.
* The site is not much responsive - Working on it.
* Text is too large and the container is overflowing to the container - Fixed.
