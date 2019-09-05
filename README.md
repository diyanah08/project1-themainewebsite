# The Maine's Website
###### Project 1: User-Centric Frontend Development - Code Institute – Band Website
This is a website that is designed for the band named “The Maine”. The website highlights the tour dates, media and albums from the band and includes a short excerpt about the band. There is also a section for their social media accounts.

## UX
My goal in the design was for new and old fans of The Maine to be able to keep up with the band’s tour dates as well as get to know the band’s repertoire of albums.
1. As an existing fan, I want to know where the band is touring, so that I can achieve get tickets to see them.
2. As a new fan, I want to know their repertoire of albums, so that I can hear their evolution through the years.
3. As a person doesn’t know the band, I want to know who they are, so that I can decide if they interest me.
4. As a person doesn’t know the band, I want to know their latest songs, so that I can decide if I enjoy their music.

## Technologies
1.	HTML
2.	CSS
3.	Bootstrap (4.3)

## Features
This site uses the starter template in Bootstrap as well as several components from Bootstrap. The HTML and CSS style is then modified to achieve the design of the website.

#### Features Left To Implement
In the future, I would like to be able to:
1.	Disable the model if form is not valid.
2.	Add the proper form to collect email address.
3.	Create a list of tour dates that is able to automatically add in new dates and update once the event is over.  

## Testing
The intended outcome for old fans and new fans user stories have been achieved.
1. Old friends are able to easily view the upcoming tour dates of the band in the Tour section by either scrolling or clicking the 'Tour' link in the navbar.
    - They are then able to get tickets by simply clicking the 'Get Tickets' button which will lead them to a separate external website for the tickets.
2. New fans are able to get to know and listen to the band's albums by clicking on the 'Albums' link in the navbar.
    - They are then able to open the albums in their Spotify.
3. A person who doesn't know the band will be able to get to know the band by:
    - Listening to their latest album by clicking the 'call-to-action' buttons at the tp of the page.
    - They will also be able to get to know what the band stands for in the About section by either scrolling down from the landing page or clicking the 'About' link in the nav bar.

The “required” attribute was added to the ‘name’ and ‘email’ fields in the form so that you will not be able to submit the form.

However, the modal still pops up when the submit button is clicked as I was not able to add in the JavaScript component.

All links that are not on the landing page will open in a new tab using 'target="_blank"'. The links have been tested to ensure that they are linked to the correct destination.

This site was tested on different browsers (Chrome, Safari, Internet Explorer, FireFox).
- When tested on Internet Explorer, it was noticed that the alignment for the About section was off and the background-color for the poem div was not compatible.

This site was also tested on several mobile devices (iPhone 6: Safari, iPad, Samsung Galaxy S9, Samsung Tablet S5 and S6). to ensure compatibility and responsiveness.


## Deployment
This site is hosted by using GitHub pages.
It is then deployed from the master branch.
When new commits are pushed, it will be automatically updated.

Website can be open directly using [this link.](https://diyanah08.github.io/project1-themainewebsite/)

My github for this website can be accessed at [here.](https://github.com/diyanah08/project1-themainewebsite)

## Credits
#### Content
Content in the About Section was written by me except for:
- Extract Y in the About section was taken from https://soundigest.com/2019/04/05/the-maine-you-are-ok-album-review.
- Poem was taken from the [description box of this video](https://www.youtube.com/watch?v=--25CSFCMM8)

#### Media
All photos from this projects were obtained from The Maine's [Twitter](https://twitter.com/themaine?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) and [Spotify](https://open.spotify.com/artist/4o0pNHbyj36LPvukNqEug0) accounts except for
- The hero-image which was obtained from [here.](https://www.thedailylistening.com/listen-the-maine-numb-without-you/
)
- The background image of the About section which was obtained from [here](https://shop.rocksound.tv/collections/the-maine/products/rock-sound-issue-251-the-maine).

Images were then edited using Paint and Microsoft PowerPoint to achieve the look for the website.

Videos for the Media section was obtained from The Maine's [YouTube Channel](https://www.youtube.com/channel/UCiBBtnxr0y43SuKEw5hUGhQ).

Albums for the album page were taken and embeded from [Spotify](https://open.spotify.com/artist/4o0pNHbyj36LPvukNqEug0).

#### Acknowledgements
This project was created by using the Bootstrap Starter Template found [here](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

The following different components were taken from Bootstrap as well.
1. [Navbar](https://getbootstrap.com/docs/4.3/components/navbar/)
2. [Jumbotron for Hero-image](https://getbootstrap.com/docs/4.3/components/jumbotron/)
3. [Modal for footer section](https://getbootstrap.com/docs/4.3/components/modal/)
4. [Card for the Media Section](https://getbootstrap.com/docs/4.3/components/card/)
5. [Dropdown for the Album Page](https://getbootstrap.com/docs/4.3/components/dropdowns/)

Components styles were then changed using an external CSS file.

Bootstrap hamburger menu for colapsible menu was taken from https://mdbootstrap.com/legacy/angular/6.2.1/?page=navigation/hamburger-menu

All icons used were taken from [FontAwesome](fontawesome.com).

##### **For educational purposes only**