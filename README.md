- [Books 2 Review](#books-2-review)
- [Introduction](#introduction)
- [UX](#ux)
  * [Project objectives](#project-objectives)
  * [User Goals](#user-goals)
  * [Developer Goals](#developer-goals)
    + [Website Owner Goals](#website-owner-goals)
  * [User Stories](#user-stories)
- [Design](#design)
  * [Inspiration:](#inspiration-)
  * [Font](#font)
  * [Colours](#colours)
  * [Icons/Images](#icons-images)
  * [Content Section](#content-section)
  * [Defensive Design](#defensive-design)
  * [Wireframes](#wireframes)
- [Features](#features)
  * [Existing Features](#existing-features)
    + [Site Features for Non-registered/Registered Users](#site-features-for-non-registered-registered-users)
  * [Features to Improve/Implement](#features-to-improve-implement)
    + [1. e-book speech](#1-e-book-speech)
    + [2. Book Linking](#2-book-linking)
    + [3. Book Recommendations for users](#3-book-recommendations-for-users)
    + [4. Theme Swaps](#4-theme-swaps)
  * [Scalable and Easy to Maintain Code](#scalable-and-easy-to-maintain-code)
    + [Make Code easier to maintain](#make-code-easier-to-maintain)
- [Technologies used](#technologies-used)
  * [Data Infrastructure](#data-infrastructure)
    + [Database Choice](#database-choice)
    + [CRUD Functionality](#crud-functionality)
    + [Data Models](#data-models)
- [Testing](#testing)
  * [Validation Testing](#validation-testing)
  * [User Stories Testing](#user-stories-testing)
    + [Automated](#automated)
    + [Manual](#manual)
    + [Testing Client Stories from UX Section](#testing-client-stories-from-ux-section)
    + [Cross Browser Testing](#cross-browser-testing)
    + [Device Testing](#device-testing)
  * [Lighthouse Audit](#lighthouse-audit)
  * [Bugs Discovered](#bugs-discovered)
    + [Outstanding Defects](#outstanding-defects)
- [Deployment](#deployment)
  * [Connecting to MongoGo DB](#connecting-to-mongogo-db)
  * [Deploying the Application to Heroku](#deploying-the-application-to-heroku)
  * [How to run the project locally](#how-to-run-the-project-locally)
  * [How to download github files and upload](#how-to-download-github-files-and-upload)
  * [Content/Media](#content-media)
  * [Code](#code)
  * [Acknowledgements](#acknowledgements)

# Books 2 Review

![Title](https://github.com/tomod24/Books2Review/blob/master/assets/images/1.png)

# Introduction

Books 2 Review is a database website where users/clients can provide a review for a particular book for others to read and share their thoughts. This website will use the information provided by registered users to provide the information. If the users register, they can use more of the features such as adding books, reviews, amends and deleting review if necessary. The site will be designed to provide a simple but powerful attractive site for users to share their thoughts and opinions. This will also give them the opportunity to also learn about which books are recommended by other users.

- Book reviewing website [https://books2review-dt.herokuapp.com/](https://books2review-dt.herokuapp.com/)
- Welcoming book review website that makes it simplistic for reviews and books to be added when they have signed up to the website. This also gives the user the ability to read others book lovers books reviews.
- This will share a book experience for other users looking for new books and encourages others to read books they have loved recently or in the past. Building a community helping each other with books to read or checkout.

# UX

## Project objectives

**Books 2 Review&#39;s main objective is to allow users to add reviews and books they have read. This is for all users who sign up to the website to share reviews and also read others readers thoughts and feelings on a book. The user will also be able to edit and delete reviews. Only admin can add books to the website. This will be for site functionality and the site being controlled by admin personal.**

## User Goals

- Easily accessible book review website for personal use sharing book opinions experiences
- Ability to add books and reviews when required
- Enjoyable experience discovering new books and adding thoughts and feelings on a book they have already read

## Developer Goals

- Demonstrate a solid understanding of MongoDB, Heroku and Python
- Build a friendly and useful book review website
- Build up portfolio with a great project
- Make the site easy to use and navigate which provides a positive experience

### Website Owner Goals

- Have an easy-to-use site that encourages users to interact with it
- Gain affiliate relationships to cross sell books

## User Stories

As a book lover and wanting to share my experiences and find more books to read I want:

- to find new books available to read
- to read reviews of books by other users and get feedback on them
- to be able to read the book description
- to be able to register for the book webpage to track my reviews
- to be able to add books of my choosing
- to have the ability to create/add reviews on any book of my choice
- To have the ability to update one of my reviews if I wish to change it
- to navigate through the web page with ease
- to add a like or dislike on the book I &#39;am reviewing
- to see the latest reviews when selecting a book to view
- to be able to search for books if a database is large or small
- the ability to delete any reviews I want to change or start again.

# Design

## Inspiration:

The book idea come from my brother due to the knowledge given about how he works in library&#39;s. The information they hold and explained the data within a library is endless. So many books are released stored and recycled. Books are only removed due to purchase, damage or loss. With this design it will start with a book and continue to grow the more users that join the bigger the data collection. This will be growth in the number of books, reviews and users on the site. Books impress users by the description of the story, the title and user&#39;s opinion of a book. Overall, the main opinion that matters is the user but if it can help others have interest then there is a bigger outcome. If a review is good it will encourage users not only to get the book being reviewed but it will also broaden the users&#39; mind. In the aspect of reading more books from the author producing more reviews and interesting others who might read similar books. Overall a book website was perfect for what is being created. Not only does it meet the requirements in providing useable information to others, it also provides a design interest and impact on the user. Therefore, I believed this would be perfect as I know how a library works in general, I understand the data aspect and believe everyone uses them for story&#39;s and to acquire knowledge. This spans into countless data.

## Font

![font](https://github.com/tomod24/Books2Review/blob/master/assets/images/2.png)

Dafont was a reliable webpage with interesting font to use therefore I have used the following (Badly Stamped). The font selected was from [www.dafont.com](http://www.dafont.com/) it was perfect and suited for the theme of the site. I had I searched through several fonts and believed this was an excellent font giving the site a different dynamic and edge. It had the style that I was looking for and gave the font a better design overall on the webpage. Examples have been provided below.

when attempting to use the font for the website the font wasnt suitable for the website. As a result a more suitbale font was selected so the website wasnt impacted in a negative way. Due to wanting the site to be alot cleaner and simple for users the option to remove the badly stamped font was decided as the webiste the more simple it is the more appealing ti can be. Creating cleaner websites is the goal as they are alot better overall instead of a complex website where there is too much going on. As a result this decision was taken and the font-family: Nunito Sans, sans-serif was selected.

## Colours

I used the colours selected above as the complicated each other. I searched several sites for good combinations of colours working well together giving a presence. The orange, white, dark grey and black worked very well for me. I believed the sight would be bright for the users and have specific criteria stand out where required. I tried several different colours to check and personally didn&#39;t find it appealing nor did it make an impact on the website when implementing the colour. The colours selected were popular across various sites such as [https://www.tailorbrands.com/blog/logo-color-combinations](https://www.tailorbrands.com/blog/logo-color-combinations). Therefore, as I had seen the colour group together and enjoyed the colours myself I decided it was best to use due to the presence it gave for the website idea and design.

![colours](https://github.com/tomod24/Books2Review/blob/master/assets/images/3.png)

## Icons/Images

With the help of font awesome I was able to implement a varied number of icons on to the page. The icons help indicate the requirement or purpose of the section. Example being sign up for the website would be a pen and image logo to upload a picture for the book. The logos give more of a design effect on the website and make it more interactive for users. I believe the icons in the right place and correct icon used bring a custom design to the site and attention to detail supplied. This helps users enjoy and appreciate the site more that it has been created with effective detail and help support users in a hidden way. There are a few examples of the icons added below to show what has been used on the website.

![icons](https://github.com/tomod24/Books2Review/blob/master/assets/images/4.png)

## Content Section

The content for website has been separated into the books that can be selected, reviews page for adding, updating, editing and deleting. On the home page the website will show the books via 3 books per row. Display the latest book at the bottom of the page. With the mobile device it will one book per row and tablet device will be 2-3 depending on size of the tablet.

For small devices this has been set to be viewed as 1 book per row. Depending on the tablet size it can be 3 books per row. I believe this can be implemented and can be improved on small devices in the future and something to work on. I believe the book should be the main object the users see this will improve the interest rate with interacting with the site for books and review information. The book site target is to capture the user&#39;s attention for new books to find and share with others. Including the objective for the users to find books with ease. Via scrolling or using the search bar to find the book they desire.

The users will have the ability to select the book present on the main page or search for a book via the search bar. When selecting a book of their choice the website will provide the user with the book details e.g., image and book description. If logged in the user will be able to add a review if they wish to do so. The user will also be able to review the latest 3 reviews on the book they are currently viewing. If there&#39;s no reviews then it will indicate no reviews available. This maybe the book hasn&#39;t been reviewed or it has been newly added. Once the user decides to add a review clicking the button, they&#39;ll be referred to a form requiring the book details and upload a book image if required.

Current format and size have been provided from amazon due to the clean book covers. Once the users upload the review, they can see the newly added view on the selected books content page. This will allow the user to add another review, amend a review or delete a review. If they add a review, they will get a time and date stamp automatically. When adding a review, the user can put a like on the book or dislike and thumb will indicate thumb up for yes, they like the book or a thumb down for no.

Users don&#39;t have access to deleting books only reviews the admins can remove books. This has been input so that other users of the books on the website or added reviews aren&#39;t reviewed in error.

## Defensive Design

The defensive design was implemented for the information supplied via the form mainly on the website. This was controlling the information input into the website when add new reviews on the website. This would prevent any fields being missing causing website retrieval problems and ensure all the information is supplied when adding any information to the database website. Another measure implemented is if the user is tampering with the website which will provide a 404 error on the website alerting the user of the issue. This is necessary to ensure the users respect and use the sight correctly and what the sites purpose is. Providing accurate and correct book information with reader views supplied

## Wireframes

Balsamiq frameworks was perfect to get a mock up design and use ideas in website layout and helped me decide site functionality. When creating the home space, it creates a wave of ideas. Designing and planning was much easier using Balsamiq frameworks previous was sketching my site design on paper and pen. If any changes are implemented then I can discuss the changes from the original idea and show how I&#39;ve improved the design. This way it will indicate the improvements and the reasoning behind changing the design.

The created wireframes below will show the design and the idea of how I wanted the website to be laid out from my ideas. I will try and match the wireframe design to the website pages displayed and improve the project as I go if I deem the change necessary. The changes will be mentioned in the final part of the Readme file showing from the original design and the end product. Websites can change when designing due to either improvements implemented or due to errors that need to be fixed and resolved.

![wireframe1](https://github.com/tomod24/Books2Review/blob/master/assets/images/5.png)

![wireframe2](https://github.com/tomod24/Books2Review/blob/master/assets/images/6.png)

![wireframe3](https://github.com/tomod24/Books2Review/blob/master/assets/images/7.png)

![wireframe4](https://github.com/tomod24/Books2Review/blob/master/assets/images/8.png)

![wireframe5](https://github.com/tomod24/Books2Review/blob/master/assets/images/9.png)

![wireframe6](https://github.com/tomod24/Books2Review/blob/master/assets/images/10.png)

![wireframe7](https://github.com/tomod24/Books2Review/blob/master/assets/images/11.png)

![wireframe8](https://github.com/tomod24/Books2Review/blob/master/assets/images/12.png)

![wireframe9](https://github.com/tomod24/Books2Review/blob/master/assets/images/13.png)

![wireframe10](https://github.com/tomod24/Books2Review/blob/master/assets/images/14.png)

![wireframe11](https://github.com/tomod24/Books2Review/blob/master/assets/images/15.png)

![wireframe12](https://github.com/tomod24/Books2Review/blob/master/assets/images/16.png)

![wireframe13](https://github.com/tomod24/Books2Review/blob/master/assets/images/17.png)

![wireframe14](https://github.com/tomod24/Books2Review/blob/master/assets/images/18.png)

![wireframe15](https://github.com/tomod24/Books2Review/blob/master/assets/images/19.png)

![wireframe16](https://github.com/tomod24/Books2Review/blob/master/assets/images/20.png)

![wireframe17](https://github.com/tomod24/Books2Review/blob/master/assets/images/21.png)

![wireframe18](https://github.com/tomod24/Books2Review/blob/master/assets/images/22.png)

![wireframe19](https://github.com/tomod24/Books2Review/blob/master/assets/images/23.png)

![wireframe20](https://github.com/tomod24/Books2Review/blob/master/assets/images/24.png)

![wireframe21](https://github.com/tomod24/Books2Review/blob/master/assets/images/25.png)

![wireframe22](https://github.com/tomod24/Books2Review/blob/master/assets/images/26.png)

![wireframe23](https://github.com/tomod24/Books2Review/blob/master/assets/images/27.png)

![wireframe24](https://github.com/tomod24/Books2Review/blob/master/assets/images/28.png)

![wireframe25](https://github.com/tomod24/Books2Review/blob/master/assets/images/29.png)


# Features

## Existing Features

### Site Features for Non-registered/Registered Users

The book review website will display the latest books on the home page for the users. From here the user can search for a book following the correct criteria in the search bar which is a minimum of three characters using keywords instead of generic words such as the, and etc. The suer can also click the book present and select book details. As a n unregistered user, they have the ability to read the book details, read the review and register. The user cannot edit reviews, add books, manage reviews or delete the reviews.

![home](https://github.com/tomod24/Books2Review/blob/master/assets/images/30.png)

The book details page when selected shows the information as required posting the latest comments on the page Maximum of 3 at this point in time. The comments will update each time a review is added for the specified book selected to complete a review. The users also see how many likes and dislikes the book has indicated by thumbs images with a up and down icon and number to indicate the amount of likes and dislikes. The book detail page allows users to edit and delete their review if it is visual via the top 3 comments. This is by selecting the collapsible review boxes and once the box jumps down the options if available to the user for their reviews, they can edit or delete the review. The users also have the options to add the review by selecting the review button which takes them to a form to complete for the book review the wish to provide.

![book_details](https://github.com/tomod24/Books2Review/blob/master/assets/images/31.png)

Registered Users

![register_users](https://github.com/tomod24/Books2Review/blob/master/assets/images/32.png)

As a registered user, the users can have the ability to login into their account and they can add reviews only the admin can add the books. This will include the details of the book title, author, description, book image and many more details. 
If the admin does not provide all the details necessary the book can’t be uploaded until all the fields have been completed.

If the user does not provide all the details necessary the book can&#39;t be uploaded until all the fields have been completed.

![add_books](https://github.com/tomod24/Books2Review/blob/master/assets/images/33.png)

Once the details have been applied correctly. The user will receive an update stating they have successfully uploaded a book.

Once updated and completed successfully the user will be able to see the book on the home page. This will be the page the user is redirected to on the order once completed.

![add_books2](https://github.com/tomod24/Books2Review/blob/master/assets/images/34.png)

The user has the ability to add reviews to the website by selecting the book details on their chosen book. This will then lead them to the book details page and from here they can select an add review button to that particular book.

![add_review](https://github.com/tomod24/Books2Review/blob/master/assets/images/35.png)

The user can then add a review the like button is automatically ticked by the user can change it to dislike the book if required by ticking the box.

![add_books2](https://github.com/tomod24/Books2Review/blob/master/assets/images/36.png)

Once the details have been applied correctly. The admin will receive an update stating they have successfully uploaded a book.

![add_books3](https://github.com/tomod24/Books2Review/blob/master/assets/images/37.png)

Edit Book Review Feature

The users can also go on to their reviews and edit if they wish to change something or delete the review. This is for users to control their rumours&#39; accordingly and if errors need amending or they change their opinion the actions can be completed. The users would select the review they posted only this would be via the profile page or on the books page if the review is still available. This is because the reviews are the three most recent revises.

![edit_review](https://github.com/tomod24/Books2Review/blob/master/assets/images/38.png)

The user can change their vote or their review details. Once complete the user can save the details and this will reflect correctly and also produce an updated message once completed.

![edit_review](https://github.com/tomod24/Books2Review/blob/master/assets/images/39.png)

Delete Book Review Feature

Users have the ability to delete any reviews they no longer wish or if they just don&#39;t want it on their profile. Only the admin has the ability to delete any reviews for any user. When selecting the delete option the user has the red button for delete to select. Once they press this button, they can&#39;t reverse the action the review will be simply deleted and they will go back to the home page.

![delete_review](https://github.com/tomod24/Books2Review/blob/master/assets/images/40.png))

## Features to Improve/Implement

### 1. e-book speech

Users will be able to play the description or short paragraph from the story. It would be for people with difficulty and people who want to hear the book out loud. It would be a great feature to have on the system.

### 2. Book Linking

Links when picking a book directing users to similar genres or other books from the author in relation to the book the user is viewing. This would require algorithms to be implemented to find the correct information.

### 3. Book Recommendations for users

When the user&#39;s login to their account on their profile not only will there be there reviews on the book but the users will also have books recommended by the website that they may interested in. This would help expand the books the users view and open up the various book options the user has and build a potential interest for the user.

### 4. Theme Swaps

The current theme is pleasant for users and matches well. The option for users to pick all the main colours such as red, green, blue, yellow etc they can pick a theme for the site they would enjoy they like. Boys blue and Girls pink for example. This would be more tailored to the users.

## Scalable and Easy to Maintain Code

### Make Code easier to maintain

Using a block content code including content read for each website main the generic design each and simple to keep everything the same and 100% accurate. This was easy for amending purposes and ensure the design was constant throughout the website. This enabled the different sites to be created a lot better and more efficiently when required. Its easy to break down the code with comments to ensure the information on the site was correct also and easy to debug code if necessary. Any issues with the code would come from the concept and not the base site block included on each page.

# Technologies used

For the website the following programming languages have been used HTML, CSS, Heroku, MongoDB and JavaScript programming languages.

- [GitHub](https://github.com/) – The project required and believed GitHub was the best for storing the projects details and easily be used for remote access when required.
- [JQuery](https://jquery.com/) - used to simplify some DOM manipulation for certain functions
- [GitPod](https://gitpod.io/) – Great toll to be sued for the development of the website and using the platform to complete the website as required. This helped fulfil the potential to complete the website.
- [Heroku](https://dashboard.heroku.com/) – Launch the application code via Heroku used via deployment
- [Materialize](https://materializecss.com/) – Helped support the coding queries necessary such as colours and grid information when necessary. The site also made footers very    easy to include.
- [Favicon](https://favicon.io/favicon-generator/) - Used to provide unique logo for the web page icon section
- [Dafont](http://www.dafont.com/) for the site font styled for a customer and unique feel.
- [Basalmiq](https://balsamiq.com/wireframes/desktop/) - Used for wireframe creation using professional tools to support the design
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools) - Audit you used it for your accessibility testing

## Data Infrastructure

### Database Choice

This project was required to be based on a NoSQL database structure so MongoDb was used.

### CRUD Functionality

### Data Models

Data stored in Books2Review MongoDB consist of these data types:

- Date
- String
- Object Id
- Boolean

**Users**

- The USERS collection ensures users are unique and helps track permissions for adding, updating and deleting data to other
- Create – users are created when a user registers for the site. A user must register if they want to add a review. The users can view the books and reviews but cant add any content or reviews personally.
- Read – users are read when logging in and when viewing the profile page.
- Update – users are not updated as this point in time future input can be contact details but as it is only an educational website personal details will not be provided
- Delete – users are not deleted on the system.

**Books**

- The BOOKS are the database collection for the information on the website and makes the website function correctly and fulfilling its purpose. Books are unique and there is only one of their kind. Books are updated by users but can be added by the admin team.
- Create – books are created by the Admin user when new books come out and they want to upload them for review they can be processed by the admin only. This is so the users can just find the book they want and review it instead of obtaining books details.
- Read – books are read by users and admin on the site. They book details will also be read when uploading to book details page and the home page.
- Update – feature is not yet implemented.
- Delete – feature is not yet implemented.

**Reviews**

- The Reviews are supplied by the users the more reviews on site the more active the site is. This tracks popular books on the website also for users.
- Create – users can create reviews on the books including admin stored on the database for all site visitors to review.
- Read – reviews can be read by all users. Visitors, admin and registered users.
- Update – users can update their review only and no other registered users. Admin can update all reviews
- Delete – users/admin can delete the reviews on site.


# Testing

## Validation Testing

I used the following websites and pasted my code into it to ensure the code had no syntax errors:

- **JavaScript -** [**https://jshint.com/**](https://jshint.com/)
- **HTML -** [**https://validator.w3.org/**](https://validator.w3.org/)
- **CSS -** [**https://jigsaw.w3.org/css-validator/**](https://jigsaw.w3.org/css-validator/)
- **Lighthouse -** [**https://developers.google.com/web/tools/lighthouse/?utm\_source=devtools**](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools)

## User Stories Testing

### Automated

Jasmine testing would be ideal in testing the book website. As we have tested during the end process of the website and nearing the end of the requirement the manual testing was suitable enough for the website.  This is due to the JavaScript on the site being minimal, only adjusting heights on the book detail page and get books page, therefore the investment in automated testing wouldn&#39;t be a beneficial action to be completed for the website. 

### Manual

Manual testing was completed on the website. This included book searches, details displayed, add and review information and many more tests that actioned during the website building progression. The details have been provided below showing the result of the testing via a desktop website, mobile and tablet. The responsive device was fine when testing on a desktop page. Therefore, attempt testing on a small platform and a medium platform would be ideal to ensure they have been built and support all platforms available.

### Testing Client Stories from UX Section

Manually testing was completed to ensure the website met the user stories requirements. This would ensure the website has been checked and satisfies the users. This including what they want the website to do and how they want it to work. A list of the requirements has been provided below for reference. This is to show the testing&#39;s made and also the results of the tests. This would help satisfy the users of the website.

### Cross Browser Testing

Various browsers were tested with the game link to ensure it would work on the browsers selected and available to use. This would ensure the website was available to a vast number of users. Giving the website a better fan base due to no limitations using the books 2 review website.

- to find new books available to read
- to read reviews of books by other users. With Easy access to review the information
- to be able to read the book description
- to be able to register for the book webpage to track my reviews
- to be able to add books of my choosing
- to have the ability to create/add reviews on any book of my choice
- To have the ability to update one of my reviews if I wish to change it
- to navigate through the web page with ease
- to add a like or dislike on the book I &#39;am reviewing
- to see the latest reviews when selecting a book to view
- to be able to search for books if a database is large or small
- the ability to delete any reviews I want to change or start again.

![testing1](https://github.com/tomod24/Books2Review/blob/master/assets/images/41.png)
![testing2](https://github.com/tomod24/Books2Review/blob/master/assets/images/42.png)
![testing3](https://github.com/tomod24/Books2Review/blob/master/assets/images/43.png)

![testing4](https://github.com/tomod24/Books2Review/blob/master/assets/images/44.png)
![testing5](https://github.com/tomod24/Books2Review/blob/master/assets/images/45.png)
![testing6](https://github.com/tomod24/Books2Review/blob/master/assets/images/46.png)

**Note - Safari is not available unfortunately I do not possess access to this system. This will be provided for users to test and view if possible. At this point in time, I cannot test if it is suitable on the application/browser available.**

### Device Testing

To enable all device were tested and various device were explored tablets and mobiles where considered to test the game on. This would ensure this works on multiple devices.

![testing7](https://github.com/tomod24/Books2Review/blob/master/assets/images/47.png)
![testing8](https://github.com/tomod24/Books2Review/blob/master/assets/images/48.png)
![testing9](https://github.com/tomod24/Books2Review/blob/master/assets/images/49.png)

![testing10](https://github.com/tomod24/Books2Review/blob/master/assets/images/50.png)
![testing11](https://github.com/tomod24/Books2Review/blob/master/assets/images/51.png)
![testing12](https://github.com/tomod24/Books2Review/blob/master/assets/images/52.png)

## Lighthouse Audit

&quot;Identify and fix common problems that affect your sites performance, accessibility, and user experience.&quot;

Accessibility testing was conducted on the site to ensure it was suitable and performing to a suitable score for users and their experience on the website. This way the site can potentially work to its maximum performance. This is completed by selected the lighthouse option on the developer tool and generating a report for the selected device. This can be mobile or desktop devices.

![lighthouse1](https://github.com/tomod24/Books2Review/blob/master/assets/images/53.png)

The result for mobile was 100 which is acceptable for the website and performance. As mentioned in the mobile review improvement to be completed as a future improvement. . (Image below first check for Books 2 review after the website was functioning)

![lighthouse2](https://github.com/tomod24/Books2Review/blob/master/assets/images/54.png)

The results for desktop are 99 which is a worthy score for a website but I would look to improve the score where possible this can be a future update and performance improvement. (Image below first check for Books 2 review after the website was functioning)

![lighthouse3](https://github.com/tomod24/Books2Review/blob/master/assets/images/55.png)

![lighthouse4](https://github.com/tomod24/Books2Review/blob/master/assets/images/56.png)

Initially the first light house check for mobile and desktop was pretty and a good result but it can be improved which would be best practice to be actioned. Ensuring its suitable for all users. Therefore, the web pages have been reviewed to ensure the code works accordingly and any errors are resolved. The functionality of the website is every important and helps with the loading as well as displaying correctly and providing clean code. For errors the mark up validation was used to ensure any issues were resolved on the order. This was key to checking the code and making sure it would be accessible for all years of the web.

Mobile Accessibility Improved Lighthouse Results

![lighthouse5](https://github.com/tomod24/Books2Review/blob/master/assets/images/57.png)

DesktopAccessibility Improved Lighthouse Results

![lighthouse6](https://github.com/tomod24/Books2Review/blob/master/assets/images/58.png)

## Bugs Discovered

![bug1](https://github.com/tomod24/Books2Review/blob/master/assets/images/59.png)
![bug2](https://github.com/tomod24/Books2Review/blob/master/assets/images/60.png)

### Outstanding Defects

- Safety measure to be implemented when deleting reviews as there is no warning asking are they sure on the system.
- Users having the ability to delete books as it would need an approval response therefore easier for the admin to ahve full contorl over deleting books if required.
- Book sizing has been sutied to the card size any image off scale or incorrectly would need size adjustments made into what size the image should be. This would prevent users uploading any size and fix scaling issues. Otherwise this could be removed. This was the .card section amending the attributes to display as required.
- Manage reviews was provided on the website for admin suers only as this has not been set up completelty this produces a 500 error. The section will be for manageing reviews and books also.  This will be completed as a future update. As there is no information to be supplied this will provide an error. The future purpose will be to ensure users have reviews deleted and confirmed. In addition books being deleted will display therefore the site would be renamed to admin managing. The reviews admin has been moved to the users profile instead. As this was more of a suitable location.

# Deployment

## Connecting to MongoGo DB

When setting up the website we used MONOGO DB as a reuslt a guide has been provided below any issues the link to MONGO DB has been provided to complete the set up required prior to the Heroku deployment. MONGO DB is a very reliable and useful databsae tool for the project requirements.

- Register and Log into [MongoDB](https://www.mongodb.com/)
- Create a new cluster
- Select the region that applys to your region free or if there is a charge. If you can select a free region that will be the best option.
- Once select scroll down checking the charges if any are applicable you can rename the cluster to a name of your choice.
- Once you have signed up create a new project giving the decided name in relation to the project or call is cluser 1 if required
- Once completed create the cluster, select your cluster and then follow the instructions then create a database.
- Name the databse relevant to your project and provide the collection name.
- From here the database allows you to various collections. Creating a collection can provide insert the documents necessary for a particualr type of database e.g. car manufacturer.
- Once the database has been completed the access will be required to pull the information to the website tool being used e.g. GitPod. Under security add a new database user if its not completed already. Ensure the password authenitcation method has been select for this example. User name and password to be updated and read and write to any database selected.
- Once the collection and user database access has been selected. The connection will be required on the system to connect the database to the gitpod.
- Select the clusters dat storage and select connect. If the mongo shell is required to be installed follow the instructions to complete the connection.
- Once completed you want to connect the applciation to your gitpod. Teh application code will be supplied and the password will be required and the dbname. this will be into the env.py file created. 

## Deploying the Application to Heroku

Heroku was used for the deployment of the website instructions have been supplied below to complete the action.

- To deploy Books2Review to heroku, take the following steps:
- Create a requirements.txt file using the terminal command pip freeze > requirements.txt.
- Create a Procfile with the terminal command echo web: python app.py > Procfile.
- Git add and git commit the new requirements and Procfile and then git push the project to GitPod.
- Create a new app on the Heroku website by clicking the "New" button in your dashboard. Give it a name and set the region to Europe.
- From the heroku dashboard of your newly created application, click on "Deploy" > "Deployment method" and select GitHub.
- Confirm the linking of the heroku app to the correct GitHub repository.
- In the heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".
- Set the following config vars:

| Key          | Value                                                                                               |
|--------------|-----------------------------------------------------------------------------------------------------|
| IP           | 0.0.0.0                                                                                             |
| PORT         | 5000                                                                                                |
| DEBUG        | FALSE                                                                                               |
| SECRET_KEY   | your secret key mongo _db user   database                                                           |
| MONGO_URI    | mongodb+srv://<username>:<password>@mybookdb.zflml.mongodb.net/<dbname>?retryWrites=true&w=majority |
| MONGO_DBNAME | your mongo db_name                                                                                  |

- To get you MONGO_URI read the MongoDB Atlas documentation [Heroku](https://docs.atlas.mongodb.com/getting-started) or refer to the mongodb guide below.
- In the heroku dashboard, click "Deploy".
- In the "Manual Deployment" section of this page, made sure the master branch is selected and then click "Deploy Branch".
- The site is now successfully deployed.


## How to run the project locally

To clone the project from GitHub:

1. Click the following link for the [GitHub repository](https://github.com/tomod24/Books2Review).
2. Click on the code button
3. A dropdown window will appear titled &#39;Clone with HTTPS&#39; - copy the link provided in the field below
4. Open your local IDE
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type in git clone paste the URL copied from earlier (step 3) alongside the git command.
7. Press Enter, and the clone should subsequently be created.
8. Once the workspace has been completed create newfile env.py file with the variables table mentioned in mongoDB (Please obtain the correct details in the guide.
9. Action/Run pip3 install -r requirements.txt to update the file and requirements.
10. Run the tool with phython3 app.py

## How to download github files and upload

To clone the project from GitHub:

1. Click the following link for the [GitHub repository](https://github.com/tomod24/Books2Review).
2. Click on the code button
3. Click the download ZIP to download a copy of the files on the repo

**Credits**

## Content/Media

- Random Key Gen – Providing secure passwords for the database enabling password creation easy but also very secure. [https://randomkeygen.com/](https://randomkeygen.com/)
- Font Awesome – Providing various symbols and logs that can be used to provide a better and cleaner design on the website with accurate and simple logos. [https://fontawesome.com/icons](https://fontawesome.com/icons)
- Materialize – Providing excellent support in implementing features and functions for the website e.g. footer, grids, colour codes and more
- Color Picker – User for the colour selection examples provided in the Design section. [https://htmlcolorcodes.com/](https://htmlcolorcodes.com/)
- Amazon – For the book images required for the website to display the book covers with excellent images provided.
- Timer Stamp – Time stamp code from stack overflow provided when implementing information. [https://stackoverflow.com/questions/36550263/how-create-a-date-field-with-default-value-as-the-current-timestamp-in-mongodb](https://stackoverflow.com/questions/36550263/how-create-a-date-field-with-default-value-as-the-current-timestamp-in-mongodb) (The right format for a date field into mongo db). The Right formatting [https://stackoverflow.com/questions/23639250/how-format-date-in-flask-using-template](https://stackoverflow.com/questions/23639250/how-format-date-in-flask-using-template)
- Auto populate the date in mongoDb [https://stackoverflow.com/questions/37782251/auto-populate-date-in-mongodb-on-insert](https://stackoverflow.com/questions/37782251/auto-populate-date-in-mongodb-on-insert)
- Method using MongoDB to update a date field by the system on update operations = [https://docs.mongodb.com/manual/reference/operator/update/currentDate/](https://docs.mongodb.com/manual/reference/operator/update/currentDate/)
-  GitHub Wiki TOC generator - Content Table creation [https://ecotrust-canada.github.io/markdown-toc/](https://ecotrust-canada.github.io/markdown-toc/)

## Code

- Book scaling on the home page. [https://css-tricks.com/snippets/jquery/equalize-heights-of-divs/](https://css-tricks.com/snippets/jquery/equalize-heights-of-divs/)
- Heroku - Deployment system used excellent tool supplying the website and connecting the information together with gitpod. [https://id.heroku.com/login] (https://www.heroku.com/)
- Materialize – Colour coding from Materialize excellent source of colours and styling used on the webpage which help make it easier selecting the colours to match and styles. [https://materializecss.com/color.html](https://materializecss.com/color.html)
- Materialize – Cards used for the books details and displaying purposes helping provide the information in a clean format for users to review. [https://materializecss.com/cards.html](https://materializecss.com/cards.html)
- Purplemoss - [https://codepen.io/purplexmoss/pen/PoPyzMW](https://codepen.io/purplexmoss/pen/PoPyzMW) acknowledgement for the 400 error template page making the design look more improved if any errors occur. Via code pen
- 505 Error - [https://codepen.io/fcasantos/pen/LJXeKP](https://codepen.io/fcasantos/pen/LJXeKP) acknowledgement from fcasantos for the 505-error template for the code when errors incorrectly appear on the website. via code pen

## Acknowledgements

- I would like to thank Anthony Ngene whose guidance and determination to make succeed keeps the work going daily. Takes the time to discuss my ideas and why and tries to guide me in the right direction asking how this will be achieved. Great mentor throughout the course and ensures am on top of my planning trying to reach my planned targets for the project completion.

- Tim Nelson and Code Institute for the template created during the course which helped to get me going with the work required.

- I would like to thank Malia Havlicek who gave me time to support me and help me with my coding concerns. Malia has also encouraged to research information and how to find the answers implement, test and ensure I check working code as it is easier to review and rewind if any issues occur. I have not only gained a great guide but also a coding friend.

- For my friends and family who encouraged me too keep going and don&#39;t forget your nearly there.
