# Mamamoo
Mamamoo is a South Korean four member girl group that debutedback on June 18, 2014 with their title track "Mr Ambiguous". 
My project is to advertise Mamamoo. The website will be used to display information about the group, including their background, schedules and their merch. This is to help promote the group and let the website be an area where current fans of the group can check and be kept up to date with everything related to Mamamoo. In doing this, I hope to be able to bring more fans for the group as well as ensure that current fans will not lose interest in them as well. Through this, we would be able to increase the popularity of the group and in turn, the sales of merchandise produced by the group.

## Design Process
This website is for mamamoo and the main purpose is to promote the group and let current fans have a website where they can check on everything related to mamamoo whenever they want. 

### User Stories
- As a person who is starting to gain interest in Mamamoo, I would want to find out more details about the group in a website that is easy to navigate and has all the information I need.

- As a long-time fan, I would want to check on the latest activities/schedules of the group and their members without needing to search all over for it. 

- As a major fan who wants to show support for the group, I would want to know what official products the group is selling, as well as how to buy them at the lowest price possible.

## Features

### Existing Features
Navigation Sidebar/Menu - Implemented to allow user to jump to different sections on the website page for faster and more efficient navigation. 

Welcome Video Background - for aesthetics and to welcome people onto the website.

About section - This section has 4 parts,a brief paragraph on who the group is, information regarding each of the members, their awards as well as their reality shows. Flex wrap was used on the member profiles for neater viewing and organisation. Tables were used to show the awards and reality shows for easier visualisation as well.


Music section - This section has two parts. First being the latest music release from the group including links to their albums through their official streaming sites as well as a youtube video with the main title track. Second part of this section includes all the albums released by the group as well as their solo albums in the order of year. For each album, there is a picture showing the album cover as well as names of the streaming platforms that the albums are on. When a user hovers over the streaming platform's name, the name will change colour and once clicked, it will lead them to the album on the streaming platform of their choice. Flex wrap was used here as well.

Merchandise section - Section includes a number of the official merchandise from the group, coming from different stores that are reputable. Fans are able to check out the stores that sell these products simply by clicking the button stating the shop name. Each listing will hover up when a pointer is on it and when someone proceeds to hover over the button with the shop name, the button will change colour. Additionally, there are pictures to provide visualisation on the products as well as the items name and price in Singapore dollars.

Newsletter sign up form - Signup form has been implemented with email verification to prevent unnecassary form applications. This signup form allows for interested people to sign up for newletters regarding Mamamoo's activities and latest updates.

Icons representing the different social media sites - All are linked to Mamamoo's Official social media accounts and when a user hovers over each icon, the opacity will be lowered.

### Features Left to Implement
Schedule section - for easy reference on all the group members solo/group activities without having to hunt for details.

## Technologies Used
HTML - https://code.visualstudio.com/, used for the bulk of the website
CSS - https://code.visualstudio.com/, used to help style the website
Javascript - https://code.visualstudio.com/, used to ensure the effectiveness of the navigation bar

## Testing
1. Newsletter Sign Up form:
- Go to the "Newsletter" Section ( can be via scrolling or clicking from the navigation bar)
- Try to submit the empty form and verify that an error message about the required fields appears
- Try to submit the form with an invalid email address and verify that a relevant error message appears
- Try to submit the form with all inputs valid and verify that a success message appears
- Notes: success message does not appear, only shows an "Your file couldn’t be accessed" message

2. Navigation Tab:
- Navigation tab con succesfully jump to each section without overlapping other text
- Notes: struggled with the placement of headings and chose to create a spacer paragraph so that the navigation tab would not cover content each section. Issue has been fixed.
- Notes: navigation bar design was changed multiple times since I originally wanted the navbar to be horizontal and turn into a small menu instead for mobile view. However, the formatting was too complicated and I opted for a normal side bar instead.

3. Youtube video player: 
- works successfully and is able to play the video
- video is able to adjust to  different browsers and screen sizes.

4. Album Navigator (under Music section)
- each link is able to go to the diffrent streaming platforms and light up(change to lilac colour) when cursor is hovering over it.
- tested the responiveness of this section on different browers and screen sizes and each album is able to go side by side or adjust to fit a whole row size.

5. Members information:
- tested the responiveness of this section on different browers and screen sizes and each member information is able to go side by side or adjust to fit a whole row size.

6. Tables (awards and reality shows):
- able to adjust to different browers and screen sizes 
- notes: face some issues with the tables overlapping other content. Issue has been fixed.

7. World Tour section:
- timeline is able to adjust to different browers and screen sizes 
- timeline is functioning and does not hinder other any other content from the site
- Notes: Had an issue with the z-index and timeline was covering the navigation bar some times. Issue has been fixed.

8. Merchandise:
- listings are able to adjust to different browers and screen sizes 
- when a cursor is hovering over a listing, the listing will float up/pop out. Otherwise, listing will stay at their normal positions.
- when the button with shop name/logo is clicked, it will lead user to website of that shop and item that the user was interested in.
- when cursor is hovering over the button with shop name/logo, the button will turn from orange to lilac.

9. Social media icons:
- icon opacity lowers when cursor is hovered over, when clicked, icons will lead user to the desired social media site.

## Credits

### Content
history, details on awards and reality shows: https://en.wikipedia.org/wiki/Mamamoo
member facts: https://kprofiles.com/mamamoo-members-profile/

### Media
album cover pictures: https://en.wikipedia.org/wiki/Mamamoo
album pictures: https://shopee.sg/mall/search?keyword=mamamoo&shop=123535631
welcome video background: taken from mamamoo's official music video, https://youtu.be/uOZ2r_UAfdc

### Acknowledgements
responsive navbar tutorial: https://www.youtube.com/watch?v=K-PEhxtC58Q
social media buttons: https://www.w3schools.com/howto/howto_css_social_media_buttons.asp
html button that links to another page: https://www.youtube.com/watch?v=ejGx2ac08lg
how to create timeline: https://www.w3schools.com/howto/howto_css_timeline.asp



