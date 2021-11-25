# Tacos Travels

Tacos Travels is a website that allows users to follow Hair O' The Dog club member 'Taco' on his various adventures on his motorbike. These adventures range from day trips, charity events, weekends away and cross country adventures. The website also aims to provide information on the vital services provided by the Blood Bikes charity in which Taco used to volunteer for as an emergency rider.


## Features 

### Site wide
* Navigation Menu
    * Contains links to the Home, Gallery and Contact pages and will be responsive on all devices.
    * This will allow users to easily navigate between the pages within the site on any size device. 
* Footer
    * This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels. The second part of the footer will contain contact information for 'Taco'.
    * This will allow the user to follow 'Taco' on various social media where they can get more up to date information that may not be displayed on the website. The contact information will allow the user to contact 'Taco' directly.
* Favicon
    * A site wide favicon will be implemented with the Hair O' The Dog clubs emblem.
    * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.
* 404 Page
    * A 404 page will be implemented and will display if a user navigates to a broken link.
    * The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need  of the browsers back button.

### Landing Page
* Landing page image
    * This will be a collection of favourite images from some of 'Taco's Travels. Images will change on a timer. 
    * This will help to immediately show the user what the website is about and help to animate the page. 

* Website information on 'Taco'
    * Information about 'Taco' and the websites purpose including an image of 'Taco' on his travels.
    * This information lets the user know what the site is about. 

* Contact form
    * A contact form will be implemented to allow users to contact 'Taco'. The form will consist of the following fields and attributes: 
        * Full Name (required, max length 50, type=text)
        * Email (required, type=email)
        * Phone number (optional, type=tel) 
        * Message (required, type=textarea)
    * This will allow user to contact 'Taco' if they have any queiries about travel destinations, charity events, club information or maybe to join him on some of his travels. 

### Gallery Page
* Gallery
    * The gallery will provide the user with photos of 'Taco's Motorcycle adventures from various trips and charity events. The gallery will be fully     responsive on all devices and allows the user to filter by categories provided in a sub navigation.
    * This will allow users that are interested in 'Taco's Travels to filter items based on the category they wish to be displayed. As the gallery is responsive it will allow the user to view content from any device. 

### Adventures
* Adventure Summary
    * Sections containing 2 photos of the trip, a paragraph about the trip and a link to the gallery page to see more photos. 
    * The sections will give the user an overview of the adventures that Taco has been on and the links will take the user to the gallery page where the user can view all the pictures that have been uplaoded for that trip. 
* More details dropdown
    * Hidden sections at the end of each Adventure Summary that will show a more detailed description of the trip which may include more details about longer trips and information about places visited along the way. 
    * These section will be hidden by default so that user can only see the summaries on the page when loaded but the user will have ability with this feature to click and view more details at the end of the summary. This will allow user to easily scroll through the page and only view details of trips that they want to read more about. 


### Existing Features

### Features Left to Implement

## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* Visual Studio Code
    * The website was developed using Visual Studio Code IDE
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
* Favicon.io
    * favicon files were created at https://favicon.io/favicon-converter/ 





## Testing 


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

### Unfixed Bugs



## Deployment

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully. 

The live link can be found here - https://gareth-mcgirr.github.io/tacos-travels/ 

### Clone the Repository Code Locally

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now of been cloned on your local machine for use.

## Credits 

* https://supfort.com/pure-css-accordion-without-javascript
    * Code was used from this site to create the accordian effect on the adventures page sections for the hidden sections for each days travels. Styles were changed to suit styling on my Website.
* https://www.youtube.com/watch?v=U-CujW5OlW0
    * Gallery page was created with inspiration from this video. I adapted code to use flexbox rather than css grid to make the page responsive on every device. 


### Content 


### Media



