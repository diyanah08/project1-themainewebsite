# The Maine's Website
###### Project 1: User-Centric Frontend Development - Code Institute – Band Website
This is a website that is designed for the band named “The Maine”. The website highlights the tour dates, media and albums from the band and includes a short excerpt about the band. There is also a section for their social media accounts.

## Demo
A live demo can be found [here.](https://diyanah08.github.io/project1-themainewebsite/)

## UX
My goal in the design was for new and old fans of The Maine to be able to keep up with the band’s tour dates as well as get to know the band’s repertoire of albums.
1. As an existing fan, I want to know where the band is touring, so that I can achieve get tickets to see them.
2. As a new fan, I want to know their repertoire of albums, so that I can hear their evolution through the years.
3. As a person doesn’t know the band, I want to know who they are, so that I can decide if they interest me.
4. As a person doesn’t know the band, I want to know their latest songs, so that I can decide if I enjoy their music.

In the design, the mobile view and the web view is also slightly different in terms of colors and text visible.
- For example, in the mobile view, the poem in the About section is hidden so has to not make the site too cluttered. As it does not affect the overall purpose of the site which is to get to know the repertoire of albums and finding out the tour dates, it is intentionally left out.

## Technologies
1.	HTML
2.	CSS
3.	[Bootstrap (4.3)](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
    - Bootstrap was used for the starter template and parts of the components such as navbar and dropdowns.

## Features
This site uses the starter template in Bootstrap as well as several components from Bootstrap. The HTML and CSS style is then modified to achieve the design of the website.

#### Specific Existing Features
1. Dropdown: Dropdown was used in the Album page to showcase the band's albums. An image was placed in the dropdown button while an iframe of the spotify link to the album was embeded into each button. This allows users to listen to snippets of the songs in each album before going to spotify itself.

#### Features Left To Implement
In the future, I would like to be able to:
1.	Disable the model if form is not valid.
2.	Add the proper form to collect email address.
3.	Create a list of tour dates that is able to automatically add in new dates and update once the event is over.
4.	Also create a calendar view for tour dates when on mobile view.

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
- When tested on Internet Explorer and Safari, it was noticed that the background-color chosen for the div in the About section was not compatible and did not show up.

This site was also tested on several mobile devices (iPhone 6: Safari, iPad, Samsung Galaxy S9, Samsung Tablet S5 and S6) to ensure compatibility and responsiveness.


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