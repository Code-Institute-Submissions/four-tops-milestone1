# ***THE FOUR TOPS***
[Milestone Project](https://rang3rdang3r.github.io/four-tops-milestone1/)
-----------------

### What is it for?
This website, designed especially for the band **THE FOUR TOPS**, will give you an overview of their past, present, and future.

### What is available?
The homepage will act as a simple display screen with navigation tools at the top of the page for linking the other pages. The logo (which always is top center of the page) acts as a quick link back to the home page.
Following on you will have the about section describing the artists and their role, this includes a photo on devices other than mobile.
On the events page you will be able to contact the band using a simple form allowing them to perform at your venue of choice, also you can follow the links provided and book the upcoming tours that are detailed with location and date on the page through an external website.
The final page allows users to listen and watch different songs from their career. A simple photo carousel with pictures will continue to cycle, embedded Spotify links in the middle of the page and finally embedded Youtube links to videos. These links all allow playing in the browser or you can go to their retrospective sites for more.
On all pages (bar the events area) you will see the alert box above the footer with a pop up modal allowing you to contact the band from any page with a simple box.
Don't forget to follow the 3 social media links to their Facebook, Twitter and Youtube accounts.

UX
--
This website will act as a good source of information for anyone of any age. 
You will be able to view tours that are coming up giving you the ability to book tickets to a specific tour. 
There are a selection of photos available throughout the page that best describe the band and their genre. Along with this music and music videos that can be played straight from the browser. 
Through alerts, modal boxes and forms scattered across each page you will easily be able to contact the group if this is what you would like.
In all the website give you access to the bands profiles, their music they make and where you can go to see them live. We then add the ability to contact the group for a more direct approach from companies and venues.

 - As a member of the public who do not know the band, this allows me to listen to their most famous music to see if i like what they produce.
 - As a returning fan they have music from their greatest albums, the ability to watch their music videos and also book upcoming tour dates.
 - From the business side - I am able to contact the band on an either social aspect or business venture through the form. Also you can see when they are next playing to get a feel for how they are live.
- The page in all allows you too see who they are, what type of music they deliver to their fans and also where and when they will be playing next

### For Mockups please use the links below:
For pen and paper mockups: 
- [Index Page](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/planning/mockups/Index%20Page.pdf) 
- [Artists Page](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/planning/mockups/Artists%20Page.pdf)
- [Events Page](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/planning/mockups/Events%20Page.pdf) 
- [Media Page](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/planning/mockups/Gallery%20Page.pdf)
For the next stage using Balsamiq Wireframe: [Click Here](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/planning/Four%20Tops%20wireframe.bmpr)

## Features

### Current Features:
#### Each Page
They all contain a logo at the top and 3 social links at the bottom.
All pages apart from the events page contain an alert box (explained later on) that has a contact pop up modal. This is hidden for mobile as not necessary. 
#### Index.html
This contains a large image that covers 100% width of the page and below a simple quote that again scales the same.
This is purely a visual page to set the theme for the rest of the content.
#### About.html
This contains another large picture at the top and also container that have the artists name/D.O.B/picture and short bio. The pictures for the artists are also links to their respective Wikipedia pages.
#### Events.html
This contains a form (that is the same as the alert box modal described above) used for contacting the band. 
Below this there is a timeline which shows upcoming live performances. These have the date and venue of the show and also a button to take you to an external page for booking the tickets
#### Media.html
There are 3 stages to this page

 - A carousel with a handful of images that continuously scroll. This is a visual aspect of the page
 - Embedded Spotify playlists that allow the user to play the audio in their browser.
 - Embedded Youtube videos that allow the user to watch certain music videos

### Features to be implemented
 - The ability to link my modal/contact forms with back end technology.
 - Consistent updates to the tour dates due to ever expanding shows.
###  Features left to implement
 - N/A

## Technology Used
#### HTML
This was the core code for the website
#### CSS
[CSS Github Link](https://github.com/Rang3rDang3r/four-tops-milestone1/blob/master/css/style.css)

 - This was the styling of my page - moving, coloring and creating the visual impact throughout the site.
#### Bootstrap 
[Bootstrap link](https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css)
 - This game me to ability to group my components together across the page using grids and helped make a more responsive website.
#### Javascript & JQuery
[Javascript Link](https://www.javascript.com)
[JQuery Link](https://jquery.com)
 - These were primarily used to create the modal box which was used for the contacting area/alert box popup.
#### Font Awesome
[Font Awesome Link](https://origin.fontawesome.com/)
 - This gave me the ability to set icons for my footer to use in the
   social media links.
#### Google Fonts
[Google Fonts Link](https://fonts.google.com/)
 - This allowed me to use a custom font 'Staatliches" throughout the pages.
#### Validators
[CSS Validator](http://csslint.net/)- Checked for errors or warnings in CSS code.
[HTML Validator](https://validator.w3.org/)- Checked for errors or warning in HMTL code.
#### Balsamiq
[Balsamiq Link](https://balsamiq.com/?gclid=Cj0KCQiAj4biBRC-ARIsAA4WaFj7R1mhRffsF_n6vSF3DMBhiXBZZxKgDnb8dNkZU5dKFewteIsJOngaAhTcEALw_wcB)
This was used for my mockups and wireframing.

## Testing
### Overall
Throughout creating my code i continued to test links and how responsive my design was. This made me change some of my choices from my Mockup stages to help improve the user experience.
Some of my links were created on my Index.html page and then copied throughout the other pages. 
 
 ### Reused code from the Index.html page
 **Nav Bar**

 - Click each link on each page to ensure they direct you to the target destination
 - Go onto Mobile and ensure they perform correctly

 **Nav Logo**
 
 - Go to Index Page
 - Click link - Should stay on that page
 - Go to other pages, click the link - This should take me back to Index page

**Alert Modal**

- Check to see it is the correct size and colour
- Click the link to allow the Modal box pop up
- Submit into required fields and submit
- Repeat the process but leave each required field blank
- Repeat the process but leave each required field with wrong information type

**Footer Social Links**

- Click each link and make sure they open a new page (with target="_blank")
- Ensure they take you to the target destination
- Repeat for each page

### Index.html
There are no other links here that aren't described above and reused for the other pages.

### About.html

#### Artists Photo Links
- Click the picture on the artist
- Check it takes you to their Wiki page
- Also check it opens in another browser (using target="_blank")
- Repeat for each artist

### Events.html 

#### Contact form
- This form was the same used as the modal box in terms of content. The same procedures were taken
-  Submit into required fields and submit
- Repeat the process but leave each required field blank
- Repeat the process but leave each required field with wrong information type

#### Tour Date Bookings
- Click each link to make sure they take you to their booking page
- Ensure they open as a new tab using target="_blank"
- Repeat for each tour date link

### Media
#### Photo Carousel
 - Check the Carousel box loads properly and continues to return to the start after the final photo
 - Click the right chevron to check the next photo loads
 - Click the left chevron the check the previous photo loads
 - Repeat on mobile and tablet

#### Embedded Audio
- Click the song i wish to play
- Wait until it loads and listen for 30 seconds to check there are no breaks
- Repeat for each box
- Check on mobile

#### Embedded Video
- Click the play button
- Wait until it loads
- Skip forward by 1 min
- Repeat for each video
- Check on mobile

#### Responsive Design

-   Each page was checked through the live preview by inspecting it in dev tools and choosing different screen sizes. I always checked the mobile first and then adapted to check it would still have the same effect on desktop.
-   Throughout project code was put through an HTML validator to make sure there were no open elements or such that was preventing the code to run smoothly. This helped to modify elements that were causing incorrect code.

## Bugs and Issues Encountered

 1. After using my initial Mockups and starting to create my page, i felt that visually my Nav bar needed to be tweeked to allow an easier user experience.
 2. On the Artists page, i wanted to have their bios side by side with pictures on each side. I struggled to keep the images inside their boxes on mobile without overflow so i decided to make them take up the entire width (bar margin/padding). Although this hasn't had an effect on the visual page, it made me stray from my original idea.
 3. I would have made the timeline element for the Events.html page central and then pushed each tour date on each side of the line. One reason why i didn't was because of time however it kept pushing my elements around and looking scruffy, especially when i increased the screen size to desktop.

## Deployment

To deploy my project I pushed my Cloud9 workspace to Github repository called **Four-Tops-Milestone1** using the command interface. 
I would do this each time i had either hit a milestone or fixed an issue/mistake i had made on multiple pages
Please find my Github Repository [HERE](https://github.com/Rang3rDang3r/four-tops-milestone1). This repository was built using the master branch.
You can find the page following [This Link](https://rang3rdang3r.github.io/four-tops-milestone1/).

##  Credits
### Content
All information gathered was from [The Four Tops Wikipedia Page](https://en.wikipedia.org/wiki/Four_Tops). I did however use the information as a placeholder and wrote in my own style as to not sound monotonous and scripted.
### Images

 - My Logo was taken from -[Here](https://fanart.tv/fanart/music/0d21b01f-21f2-419b-8d98-4158ba0c0aa4/hdmusiclogo/four-tops-574acbb37a42c.png)
 - My background images were taken from   
   [Index Page](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQt63_AP8_4WZIJTCeA_zj_7GaufO8jONFoxFnCX_84IOoy51a4Cw) / [About   page](https://a3-images.myspacecdn.com/images03/21/7b4cdab18c9b47899208c7cb31635454/600x600.jpg) / [Events Page](https://www.soul-source.co.uk/uploads-soul/cms-records/monthly_2018_02/four-tops-uk-tour-2018.jpg.bbd52fc20325508c8239248d8569c24d.jpg)
 - My Artist Images were from
   
 - [Levi Stubbs](https://littleshop.fandom.com/wiki/Levi_Stubbs) / [Abdul Fakir](https://mediamass.net/jdd/public/documents/celebrities/1209.jpg) / [Renaldo Benson](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjz6tmXlL7gAhWgA2MBHRbIAPwQjRx6BAgBEAU&url=https%3A%2F%2Fthedeadones.wordpress.com%2Ftag%2Frenaldo-benson%2F&psig=AOvVaw1GadozaYENf79aWe-veT4M&ust=1550334479858597) / [Lawrence Payton](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjW9Km1lL7gAhUi1uAKHcrCBrsQjRx6BAgBEAU&url=https%3A%2F%2Fwww.facebook.com%2FFourTops%2Fphotos%2Fhappy-heavenly-birthday-to-four-tops-tenor-lawrence-payton%2F10155627491993918%2F&psig=AOvVaw0P-KiJ9jYk_qsBTbG_-4MD&ust=1550334546544915) / [Theo Peoples](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjbk4jHlL7gAhUlD2MBHQ-oBPoQjRx6BAgBEAU&url=https%3A%2F%2Fwww.last.fm%2Fmusic%2FTheo%2BPeoples&psig=AOvVaw1YUtZMrWJWDfavr60Itt4t&ust=1550334590709593) / [Ronnie Mcneir](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwia2NbrlL7gAhWB2OAKHYfVBG8QjRx6BAgBEAU&url=https%3A%2F%2Fsecondhandsongs.com%2Fartist%2F98802&psig=AOvVaw0Yg5kb6heTwhQOU6CF2ZtR&ust=1550334625245490) / [Roquel Payton](https://www.discogs.com/artist/837940-Roquel-Payton) / [Harold Bonhart](http://www.zimbio.com/Harold+Bonhart/pictures/pro)
 - My Carousel Images were from  
  [1](http://www.northernsoul45s.co.uk/product_detail.asp?id=15484) / [2](https://ichef.bbci.co.uk/images/ic/960x540/p01bqpdf.jpg) / [3](https://i.pinimg.com/originals/1b/ce/44/1bce44e7810de3abe6b70314bd9c12e5.jpg) /  [4](https://i2-prod.mirror.co.uk/incoming/article9081511.ece/ALTERNATES/s615b/GettyImages-88185813.jpg) / [5](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJJXLbRtQk4Cq1NbsGbuCcive_ahUl7XShrEmoGFGBlrUHxkr4DA)

### Media
I used the embedding feature built into Spotify and Youtube to bring the content onto my page

 - The Spotify Playlists are from [Here](https://open.spotify.com/artist/7fIvjotigTGWqjIz6EP1i4?si=8Yrs0VMiRL6DeTQbrsfd2g).
 - The Youtube Links are from:
[Cant Help Myself Video](https://www.youtube.com/watch?v=qXavZYeXEc0) / [Indestructible Video](https://www.youtube.com/watch?v=adsD503UmQc) /
[Loco In Alcupolco](https://www.youtube.com/watch?v=ZDO6_R_7S0Q) /
[Baby I Need Your Loving Video](https://www.youtube.com/watch?v=KUOntQocGWk)

### Tour Dates
All of the links where taken from Viagogo's website [Here](https://www.viagogo.co.uk/Concert-Tickets/R+B-Urban-Soul/Four-Tops-and-Temptations-Tickets)

### Acknowledgements

 - Thank you for the Slack community for giving guidance and for general tips and tricks.

 