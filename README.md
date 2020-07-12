![Responsive website images](/README-attachments/responsive-screenshots.JPG "Responsive website images")

# **MILESTONE PROJECT ONE**

This project is based on my experience as a Quantity Surveyor (QS).  The website presents key data about construction projects, including descriptions,cost data, project timelines and a small gallery of images for users to refer to when needed.

Whilst I have utilised concepts/names/images from my current employer / project, the data used is not accurate.  If fully implemented, the webpage would summarise and compare a selection of projects from Wembley Park, putting at the fingertips key information that non-QS client body stakeholders can look up on-demand.  The information may be presented to non-project stakeholders (e.g. funders), which will give a snapshot of data that they may compare against other projects.


## **UX**

### **Who is the Website for?**

The Website is primarily for Developer Clients, Development Managers and Project Managers ('clients'), who work alongside the QS.  The QS will ensure the data is correct and up to date.


### **User Stories**

My experience as a QS has led me to the following conclusions:-

* Clients regularly ask for high level cost information on projects, they do not store the data themselves.

* Information is normally maintained offline in a variety of formats and locations, which may not be consistent.

* Records that collate information are normally rare and if implemented, poorly maintained and not updated frequently.

* Clients will request information; there is often a time-lag to deliver that information due to the need to locate it.

* Delivery of information can sometimes be rushed, resulting in poor presentation, incomplete information or even inaccurate due to the above factors.

By implementing a website that provides basic but key information for clients, the QS will ensure that information is correct and uploaded timeously, and be available on-demand for clients.

I believe clients will really appreciate this level of access to information, as the information is often sought for time-critical reasons and ensure that information is presented in a consistent and professional manner.


### **Functions of the Website**

The functions of the website are to:-

1. Provide a 'lite' repository of projects with key information for stakeholders to access data on-demand.

2. Users will be able to discern from each Project page:-

   * A high level description of the project - this will allow users not familiar with the project to learn important information about the project. The content may include a description of the building as a minimum, but may be extended to include other key information like areas of buildings, the number of apartments, tenure types, etc.  This could be included in future interations of the website.

   * The project timeline will provide users with the overall duration of the project, from early design and planning stages through to construction.  The full detail of a project programme is not often recorded, often limited to construction durations, the final, longest and period of greatest expenditure.  However, the overall duration is obviously important and other parts of the programme can be useful and informative, too.

   * The cost breakdown will provide users with high-level, key cost information.  The information is displayed on a cost per sqft basis, rather than the total cost.  Whilst the total cost is obviously important, users will ask for the cost per sqft 9 out of 10 times in order to compare to other projects, and utilise the information for planning future projects.

   * A gallery has also been included so users may see how the project appears.  Some users may use the site to refer for information, but may not have had any involvement in the project, so will be particularly relevant.

3. The Overview page summarises key aspects of the Project pages:-
   * The timeline shows overlapping construction (only) durations. As the construction duration is the most visible and cost significant period of the project, the Overview page limited the timeline to this aspect for comparison purposes.
   * A benchmark of the Projects included displays a comparison of the building costs per sqft.  As noted above, the cost of a project will be frequently sought by clients.  This graph also displays the average cost, which users will also want to know.

4. The footer includes:-
   * A site map of Wembley Park with locations of the Projects, and
   * Website links to the corporate websites.


## **Design**

### **Mobile v. Desktop**

The site was developed with a desktop approach primarily, but still mobile-friendly.  Most users will access the website from their computer whilst working, but there may be occassions when they need to access data on-the-go for quick reference.

With this in mind, the site has two variants to reflect the desktop / landscape and mobile / portrait variants.  As such, I have utilised one breakpoint at Medium / 768px.

The website will still be useable on portrait screen sizes at this size.  The website also has a maximum width of 1200px maintain design ratios on extra large screens.


### **Key concepts**

* Limited scrolling - the page should largely be visible on one desktop screen.
* Continuity of page design across the pages and minimal variation in the design of each page.
* Predominatly white screen and limited colour pallette and backgrounds to focus on the data presented.
* Graphs / Charts - being able to incorporate charts was very important for presenting the cost data.


### **Wireframe**

Use of Figma to develop key concepts into framework to commence web development.  Two pages were worked up, for desktop and mobile, in the knowledge that the basic page design would be replicated across the pages.

A copy of the original wireframe can be found [HERE](README-attachments/Wireframe.pdf)

Whilst my wireframe did not incoproate the footer, I knew that I would likely want to add this at a later point.  The contents would be minimal and yet to be decided, as the would be subsidiary to the other information provided.


### **Colours**

To maintain a colour theme that is consistent with the logos of Quintain and Wembley Park, a primary colour pallette was developed from the Quintain logo.

The main colour use for fonts and borders is limited to the same colour as the Quintain logo.  Where greater depth or diversity of colours were required for the likes of graphs, a fuller pallette was developed by using Paletton.

The colour pallette can be viewed [HERE](http://paletton.com/#uid=c0w3k0Z3N0k6hjd2BtG4vnW82ekcH9w)

The Wembley Park logo is orange and was not deemed suitable for the primary pallette, but still appropriate for highlighting or drawing attention to items against the primary pallette.


### Typography

The Montserrat font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Montserrat is a clean font used frequently in programming, so it is both attractive and appropriate.

Whilst acknowledged that this font has been used frequently in the Code Institute course to date, after experimenting with a few other fonts, I still felt that it is the most appropriate font to use for this project for the reasons noted.


### Imagery

As the website is meant to be functional, there is no background images and limited background colours utilised to maintain a clear, crisp display that is functional and distraction-free for users.  Whilst images are of course important to provide context and understanding to a user, they are limited to the gallery (images of the Park and the projects) and corporate logos.


## Features

### Responsive

* Site is suitable for mobile through desktop displays.
* Navbar is responsive to the display size.  Whilst a bootstrap navbar could have been implemented for both, I wanted to have the flexibility to implement different features on the Navbar on larger displays.
* Gallery is responsive to display size.  
  * On large screens, the gallery supports a solid background in the container to balance the size of the images with the content above.  The images are close in size to a single column width above, and the addition of the background provides a transition between the 2 columns above / full page width and the image.  To utilise the space, the Prev and Next icons were pushed left and right respectively, and enlarged.  

    ![Gallery on large screens](/README-attachments/gallery-large.png)

  *  On smaller screen, the carousel reverts without a background, and now relates to the single column width of the content above.

        ![Gallery on large screens](/README-attachments/gallery-small.png)

### Interactive Elements

* Dropdown images of projects over Navbar items on medium screens
* Timelines open in Bootrap modals
* Scrollable gallery in Bootstrap carousel
* Map of the project location appears on 'click' by use of Bootstrap collapse


### Existing Features  

#### The Pages

1. **Overview Page**  
Purpose of this page is to provide an overview and comparison of the projects at Wembley Park.

2. **Project Page**  
Included one for each project.  Purpose of these page is to provide further detail and provide specific project images.

#### Key Features of Pages

1. **Navigation Bar**

    On large screens, an image of the Project appears when the cursor hovers over the link:-
    ![Navbar hover](/README-attachments/Navbar.gif)  
    As the project name may change over the lifetime of a project, some users who may not be aware of changes can easily identify the project from the image.

2. **Timeline**
    * On the overview, this project compares the project construction timelines
    * On the Project pages, this provides additional timelines for the planning and design timelines. 
    * Durations were modified from default to Quarters, which is commonly used for measuring time in construction.  
    * Hovering over the bar provides the detailed date information and duration for ease of reference in the Tooltip.
    ![Timeline Snip](/README-attachments/Timeline.png "Timeline")  


3. **Benchmark Comparison / Cost Breakdown**
    * The Overview page has a bar chart that compares the construciton costs on a £/sqft basis of each Project, and the average.  
    ![Bar Chart](/README-attachments/barchart.JPG "Bar Chart")
    * The pie chart on the Projects' pages show a breakdown of that cost into an elemental format.
    ![Pie Chart](/README-attachments/piechart.JPG "Pie Chart")

4. **Gallery**

    The gallery shows a selection of images from across the Park on the Overview, and of each building for the Projects.

5. **Footer**

   The footer contains:-

   * Project Map - a map showing the locations of the Projects will drop down below the footer when activated.
        <div style="height: 0; padding-bottom: calc(35.31% + 35px); position:relative; width: 100%;"><iframe allow="autoplay; gyroscope;" allowfullscreen height="100%" referrerpolicy="strict-origin" src="https://www.kapwing.com/e/5f0a1c4df828360015c7db75" style="border:0; height:100%; left:0; overflow:hidden; position:absolute; top:0; width:100%" title="Embedded content made with Kapwing" width="100%"></iframe></div>
   * Corporate website links - links to the Quintain website and Wembley Park websites are included in the footer.  The logos enlarge when the cursor hovers over:-  
   <img src="/README-attachments/footerWP.gif" height="40" width="40" alt="Wembley Park logo footer GIF">
   <img src="/README-attachments/footerQ.gif" height="40" width="40" alt="Quintain logo footer GIF">



### Features to Implement in the Future

* Nr of Projects - add more projects to the website.
* Addiitonal project information - rather than make the page longer, add further carousels to the two columns so that a user can rotate through.  Aspects may include:-
  * Within the Overview: Building Areas, Apt numbers, tenure types;
  * within the Cost Breakdown: Total Cost, Cost per Apt.
* Link data to a database, so that they can be updated more easily.


## Technologies Used

### Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 

### Frameworks, Libraries and Programmes Used 

* [Bootstrap 4](https://getbootstrap.com/)  
Bootstrap was used to assist with the responsiveness and styling of the website.

* [Google fonts](https://fonts.google.com/)  
Google fonts were used to import the 'Monserrat' font into the style.css file which is used on all pages throughout the project.

* [Google Charts](https://developers.google.com/chart/)  
Google Charts was used for displaying data in graphical format, including timelines, bar charts and pie charts.

* [Google Maps](https://www.google.co.uk/maps) including [Styling Wizard](https://mapstyle.withgoogle.com/)  
Google Maps was used in the footer to provide locations for the Projects.  Functionaly of the maps was limited in terms of zoom, map type and points of interest to maintain a simple viewport of the Park and Project locations.  

* [Popper.js](https://popper.js.org/)  
Popper.js came with Bootstrap to make the popovers operation responsive.

* [jQuery](https://jquery.com/)  
jQuery came with Bootstrap to make some of the components operate in JavaScript.

* [Git](https://git-scm.com/)  
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

* [GitHub](https://github.com/)  
GitHub is used to store the projects code after being pushed from Git.

* [Pixlr](https://pixlr.com/)  
Pixlr was used to resize images and editing photos for the website.

* [Figma](https://www.figma.com/)  
Figma was used to create the wireframes during the design process.

* [Paletton](https://paletton.com/)  
Paletton was used to create a pallette of colours that supported the main colour of the website, which is based on one of the company logos.

* [Kapwing](https://www.kapwing.com/)
Kapwing used for editing videos and creating GIFs used in this README file.

* [Screen Recorder](https://chrome.google.com/webstore/detail/screen-recorder/hniebljpgcogalllopnjokppmgbhaden)  
Screen Recorder used for creating videos (edited in Kapwing) of website features in operation.


## Testing

**Testing is still to be undertaken**

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

* [W3C Markup Validator](https://validator.w3.org/) - Results
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - Results


### Further Testing

**Testing is still to be undertaken**

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
* The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
* A large amount of testing was done to ensure that all pages were linking correctly.

### Known Bugs

* On the timeline, the dates are a mixture of regular and bold text.  It does not appear possible to format this axis on this particular chart type.
* The Chart size does not respond on page re-sizing without re-freshing.
* The Pie Chart does not show the Total, only a breakdown of the values.


## Deployment

The website has been deployed on GitHub and is currently publicly accessible. 

The development of the website has been undertaken on Gitpod.

The steps from start to present were:-

    1.Creation of repository on GitHub, utilising Code Institute template.
    2. Launch of repository on Gitpod.
    3. Utilise Git to push content back to GitHub.  This was undertaken at regular intervals throughout the development of the website.
    4. Deployment of the webpage was implemented by
        - Going to the 'Settings' of the repository,
        - Scrolling to 'GitHub Pages' section,
        - Selecting 'master branch' of the Source dropdown menu


## Credits

### Content

All content was written by the developer.

### Media

All Images are the ownership of Quintain, my employwer.

### Acknowledgements

Thank you to my mentor for feedback and advice given throughout the project.