# Band website - The Monkees

This is a front-end only website for the band 'The Monkees'. The purpose of this website is to target their primary audience which is their fans as well as potential fans enabling them to see and hear clips from their back catalogue and any new material as it becomes available.
I was also tasked with giving the band the ability to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
The final element was to aid the band in creating their social media presence by linking to their social media platforms such as Facebook and Twitter.

Website link below:

https://jordenci.github.io/first-milestone-project/
 
## UX
 
This website was designed for existing and potential fans of the monkees to give them the ability to see and hear the bands music/videos as well as give them the ability to book events if they wish too.

### User stories

- As an existing fan I want the ability to book the band out for events so I can have them play at my wedding.
- As an existing fan I want the ability to follow the band on all available social media sites.
- As a potential fan I want to learn more about the band to see if they are for me.
- As an existing or potential fan I want the ability to listen to the bands music for enjoyment but also to see if i enjoy it.
- As an event planner I need the ability to contact the band to book events for my clients.
- As a marketing agency we need to be be able to contact the band for oppertunies to promote them.

## Features

#### Across the entire site

- Navbar: Allows all users to navigate to any part of the website without the use of browser 'back' and 'forward' buttons.
- Collapsed Navbar: Gives all users the ability to navigate the site whilst in mobile view without taking up realestate.
- Social media links: Allows users to follow the band on all social media platforms available generating more popularity with the band.

#### index.html

- Call to action bar: Immediatly makes those who are interested aware that bookings are now availbile for the bands latest tour and gives a link to the bookings page.
- 'Read more here' links: Allows the potential fans to click through to the full wikipedia pages to learn more about the band and its members.

#### tourdates.html

- Bootstrap table: This table was used to neatly present the bands upcoming tours and gives potential and exisitng fans the ability to purchase tickets to the events.

#### music.html

- Spotify playlist: Potential and exisitng fans can use this playlist to either simply ejoy the bands music or get a guage if this is the type of music they are interested in.
- Youtube videos: As above potential and exisitng fans can use this to enjoy.
 
#### contact.html

- Contact form: This form can be used either for existing fans to book events, event planners looking to hire the band or even just for general queries using the 'other info' box. This gives the band an easy way to manage any contact requests.
- Testimonials: The testimonials are also placed directly next to the contact form. This gives the person who is interested in booking/contacting the band confidence to continue with their booking request.


### Features Left to Implement

In the future I would like to impliment the below features.
- The ability to purchase full albums from the site to genetate revenue for the band.
- Some form of review/trip advisor type funtion where people interested in booking would be able to see multiple reviews on the bands past private performances.
- A merchandising page where fans can purchase all sorts of band apparel.
- A forum where anyone can get together to discuss all things related to the band. This would be a great way to to drive continued traffic to the site.

## Technologies Used

- [Bootstrap 3.3.7](https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css)  
     - This was used for the Navbar, grid system used throughout the site and the table in the 'tourdates' page.

- [Font Awesome](https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css) 
     - This was used in the footer for the social media icons.

- [Google Fonts](https://fonts.googleapis.com/css?family=Chivo:300,700|Playfair+Display:700i) 
     - I used a combination of Chivo & Playfair+Display across the site.
    
- [Hover.css](https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css) 
     - I used this to give the clickable links throught the site (the social links for example) the Hover Grow effect to give the user confirmation the link is clickable.

## Testing

- I used [This HTML validator](https://validator.w3.org/) to ensure my code was legal.
- i used [This CSS validator](https://jigsaw.w3.org/css-validator/) to ensure my CSS was legal.

1. New user wanting information on the band:
    1. User lands on the 'about' page first.
    2. User reads the 'about us' section however still wants more information.
    3. User clicks 'read more here' link that directs them to the wikipeadia as a seperate tab ensuring they still have access to the site.
    4. User still wants more information on the individual band members. therefore processed to follow the 'read more' links beneath each members bio which directs them to their specific wikipedia as a seperate tab.

2. Existing fan wants to follow all the bands social media:
    1. Social links are located in the footer of each page to ensure visibility across the site.
    2. Each social links through to their relevant site for the fan to follow.

3. Fan wants to book tickets to the bands tour:
    1. User lands on the 'about' page where there is a call to action banner across the top of the page indicating tour dates are available.
    2. User clicks through and lands on the 'tour dates' page where they can select which event they are interested in attending.
    3. Finally the user can click through using the 'purchase here' links to make their purchase for the event tickets through the relevant site.

4. Existing or potential fan wants to hear/see the latest music:
    1. User selects Music tab fromt he Navbar.
    2. Users are immediatly presented with the bands latest audio tracks as well as some video clips.
    3. Due to the location of the social media being in the footer fans could also click directly through to the youtube site to watch more videos.

4. Contact form:
    1. Go to the "Contact" page
    2. User may have not been 100% about booking however the testimonials left by a happy wedding couple and a managment team convince them to continue on with the booking.
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify.

## Viewport and responsive testing

1. I designed the site similiarly to the cv site where i built the Navbar and the footer before creating the content of the pages.
2. With the help of bootstrap I was able to create a responsive colapsing navbar.

### index.html

1. From a mobile view each Div and item within the Div sit vertically onto of eachother for comfortable browsing.
2. My site wide alert with information about upcoming tours is hidden on XS viewport.
2. When the viewport goes above mobile the primary image is then floated to the right enabling the text to wrap round the left of the image, the rest of the page remains in the verticle setup.

### tourdates.html

1. From a mobile view this is vertically alligned.
2. We start with the background image at the top of the band playing live.
3. Below we have the bootstrap table that displays all the information regarding the events.
4. This format also works in bigger viewports so no media queries required.

### music.html

1. From a mobile view each item on this page are stacked vertically. This was set with bootstraps col-xs-12 function.
2. When moving to larger viewports the 3 music blocks take up 1/3 of the page giving them a horizontal view. This was achieved with bootstrap col-md-4.
2. The videos were essentially the same however due to them being less responsive I needed to set the with of the items to 100% at full desktop viewport however only 70% between mobile and desktop. This allowed the videos to keep spacing between each of them but not be stretched on mid sized screens.

### contact.html

1. The contact page is also setup in a verticle setup in mobile using the col-xs-function.
2. On larger viewports the contact form and the testimonals have half the page each using col-md-6.
3. With the contact form I also hid the lables for the date and & time using the bootstrap 'hidden-xs' class on the label. I also gave the date and time the col-xs-12 funtion to stack neatly in mobile however a col-md-4 for better spacing in desktop.

## Deployment

I used GitHub Pages to deploy my website by following the steps below:

1. I have created a repository in GitHub.

2. I initialised git from the terminal in Cloud9:
  
    `git init`

3. I added the files that I was working on to the Staging area by using: 

    `git add .`

4. I ran the commit command with the first commit

    `git commit -m “initial commit`

5. I copied from GitHub the following path and I have run it in the cloud9 terminal in order to indicate where is my remote repository:

    `git remote add origin https://github.com/JordenCI/first-milestone-project`

    `git push -u origin master`

6. Then from my GitHub repository I have gone to settings, I have selected the master branch, I have saved and the website was published at:

    https://jordenci.github.io/first-milestone-project/ 

7. After this was done I have ran regular commits after every important update to the code, and I pushed the changes to GitHub pages.


### Content
- The text for 'about us' was copied from [The Monkees Wikipedia article](https://en.wikipedia.org/wiki/The_Monkees)
- The text for the member info was copied from their respective wikipeadia pages.

  - [Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician))

  - [Micky Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz)

  - [Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith)

  - [Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork)
  
### Media
- Most media used through the site were the assets provided with the exception of the below.

1. Band Logo & testimonal photos.
  - These were found via Google Advanced search function.  

### Acknowledgements

- I received inspiration for this project from a combination of the Whiskey Drop mini project as well as the CV mini project. I also found bootstraps documentation very helpful.