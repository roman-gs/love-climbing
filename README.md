# Portfolio Project 1 - HTML/CSS Essentials: Discover Climbing

[Discover Climbing](https://roman-gs.github.io/love-climbing/index.html) is a website intended to explain the differences between the three main disciplines of sport climbing. It allows climbing enthusiasts to get a better understanding of each discipline's characteristics and subscribe to the website newsletter. Visitors can also watch professional climbers perform their art in the Videos section. 

It was developed as part of the first module in the Full Stack Software Development course dispensed by the [Code Institute](https://codeinstitute.net), using HTML & CSS.

![Multi-device-test](/assets/readme-images/amiresponsive.jpg)

## Repository:

You can find the Github repository [here](https://github.com/roman-gs/love-climbing).

***

## Features:

- ### The Navigation bar:

    - Featured at the top of all 4 pages (Home, Videos, Newsletter & Thank you), it contains:

        - on the left the clickable title for the website that will take the user back to the Home page
        - on the right, the links to the different pages of the website
    
    - The active page title is underlined to help the user better navigate the website

    ![Navigation-bar-image](/assets/readme-images/navbar.jpg)

- ### The main image & quote:

    - The main image represents a climber who raises their arms after arriving at the top of the mountain. It's present on all pages of the website except for the "Thank you" page.
    - It is accompanied by an inspirational quote about climbing

    ![Main-image-and-quote](/assets/readme-images/main-image-quote.jpg)

- ### The "Disciplines" section:

    - This section contains three short paragraphs outlining in plain words the main differences between the three main disciplines

        1. Lead climbing
        2. Speed climbing
        3. Bouldering

    ![Disciplines-section](/assets/readme-images/disciplines-section.jpg)

- ### The social media links:

    - This section contains three icons for the main social media that will open in a new window when clicked:

        - a link to the developer's Linkedin profile
        - a link to Facebook home page since the website doesn't actually have a Facebook account
        - a link to Instagram  home page since the website doesn't actually have a Facebook account

    - They are shown on all 4 pages of the website

    ![Social-media-links](/assets/readme-images/social-media.jpg)

- ### The Videos & link to IFSC Youtube channel:

    - This section shows one video (hosted on youtube) per discipline.
    - After the videos is a link to the official IFSC youtube channel

    ![Videos](/assets/readme-images/videos.jpg)

- ### The newsletter sign up form:

    - The form has a title, a submit button and three required fields:
        - First name 
        - Last name 
        - Email (will only accept an email)
    - It brings you to a "Thank You" page once successfully submitted. 

    ![Sign-up-form](/assets/readme-images/signup-form.jpg)
    ![Thank-you](/assets/readme-images/thank-you.jpg)

***

## Testings:

- I tested that this page works on different browsers: Chrome, Safari and Firefox

- I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the DevTools device toolbar

- I confirmed that the links in the navigation bar and the links to the social media work (social media open in a new tab of the browser)

- I confirmed that the videos can be played and the sound works 

- I confirm that all the fields of the form work along with the submit button and successfully completing the form takes the user to the "Thank you" page

***

## Bugs:

### Solved:

- Found a bug where the "Hero" didn't appear on the image when the website was visited from a medium or small screen. 

    - Fixed by uploading a resized version of the same picture with new media queries for medium and small screens.

    ![Bug-image](/assets/readme-images/bug.jpg)

***

## Validator testings:

### HTML:

- No error or warning were returned when passing through the [W3C validator](https://validator.w3.org/)

### CSS:

- No error or warning were returned when passing through the [W3C CSS validator](https://jigsaw.w3.org/css-validator/)

### Accessibility:

- Scored all greens using Lighthouse in Devtools.

![Lighthouse](/assets/readme-images/lighthouse.jpg)

***

## Deployment:

The site was deployed to [GitHub pages](https://github.com/roman-gs). 

### To deploy to GitHub Pages:
- Log into GitHub and locate the repository
- Navigate to the "Settings" tab 
- Click on "Pages" on the left pane
- Select "Main" in the drop-down menu called "Branch" 
- Click on "Save"

### To Fork the Repository:
- Log into GitHub and locate the repository
- Click on "Fork" in the top right corner 
- Select "Create Fork"

### To create a local Clone:
- Log into GitHub and locate the repository
- Open the "Code" drop-down menu in the top right corner
- Copy the URL from under the HTTPS tab
- In your IED, open Terminal.
- Change the current working directory to the location where you want the cloned directory.
- Type git clone, and then paste the URL you copied earlier.
- Press "Enter" to create your local clone.

***

## Credits:

### Content & Media:

- The image in the header was taken from [Pexel](https://www.pexels.com/)
- The text in the Disciplines section was taken from [Wikipedia](https://www.wikipedia.org)
- The videos are taken from the official [IFSC Youtube channel](https://www.youtube.com/c/sportclimbing/videos)
- All icons coming from [Fontawesome](https://fontawesome.com/)
- Fonts coming from [Google-fonts](https://fonts.google.com/)

### Code:

- Code was mostly taken from what I've learned in the Code Institute HTML & CSS Essentials course including the Love Running project walkthrough. 

