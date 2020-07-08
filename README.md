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

* QS's will maintain records, but often not in an immediately presentable format.

* Records are normally maintained offline in Excel.

* Clients request information and there is often a time-lag to deliver that information.

* Delivery of information can sometimes be rushed, resulting in poor presentation, incomplete information or even inaccurate.

By implementing a website that provides basic but key information for clients, the QS will ensure that information is correct and uploaded timeously, and be available on-demand for clients.

I believe clients will really appreciate this level of access to information, as the information is often sought for time-critical reasons and ensure that information is presented in a consistent and professional manner.


### **Functions of the Website**

The functions of the website are to:-

1. Provide a lite repository of projects for key stakeholders to access data on-demand.

2. Users will be able to discern from each Project page:-

   * A high level description of the project - this will allow users not familiar with the project to learn important information about the project.
   * The project timeline will show users the overall duration of the project, from early design and planning stages through to construction. 
   * The cost breakdown will provide users with high-level, key cost information which may be compared to other projects.
   * A gallery has also been included so users may see how the project appears.

3. The Overview page summarises key aspects of the Project pages:-
   * The timeline shows overlapping construction (only) durations. (As the construction duration is the most visible and cost significant period of the project, the Overview page limited the timeline to this aspect for comparison purposes.)
   * A benchmark of the Projects included allows for a comparison of the building costs per sqft.

4. The footer includes:-
   * A site map of Wembley Park with locations of the Projects, and
   * Website links to the corporate websites.


## **Design**

### **Mobile v. Desktop**

The site was developed with a desktop approach primarily, but still mobile-friendly.  Most users will access the website from their computer whilst working, but there may be occassions when they need to access data on-the-go for quick reference.


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

As the website is meant to be functional, there is no background images and limited background colours utilised to maintain a clear, crisp display.  Whilst images are of course important to provide context and understanding to a user, they are limited to the gallery.


## Features

### Responsive

* Site is suitable for mobile through desktop displays.
* Navbar is responsive to the display size.  Whilst a bootstrap navbar could have been implemented for both, I wanted to have the flexibility to implement different features on larger displays.
* Gaallery is responsive to display size, supporting a background in the container on larger screens, but no background and pictures maximum width on smaller screens.


### Interactive Elements

* Dropdown images of projects over Navbar items on medium screens
* Timelines open in Bootrap modals
* Scrollable gallery in Bootstrap carousel
* Map of the project location appears on 'click' by use of Bootstrap collapse


### Existing Features  

* Overview Page - purpose of this page is to provide an overview and comparison of the projects at Wembley Park.
* Project Page (one for each project) - purpose of this page is to provide further detail and provide specific project images than the Overview page.
* Timeline - on the overview, this project compares the project construction timeelines.  On the Project pages, this provides additional timelines for the planning and design timelines.
* Benchmark Comparison / Cost Breakdown - the Overview page has a bar chart that compares the construciton costs on a £/sqft basis of each Project, and the average.  The pie chart on the Projects' pages show a breakdown of that cost into an elemental format.
* Gallery - shows a selection of images from across the Park on the Overview, and of each building for the Projects.
* The footer contains:-
   * Project Map - a map showing the locations of the Projects will drop down below the footer when activated.
   * Corporate website links - links to the Quintain website and Wembley Park websites are included in the footer.


### Features to Implement in the Future

* Nr of Projects - add more projects to the website.
* Addiitonal project information - rather than make the page longer, add further carousels to the two columns so that a user can rotate through.
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

* Popper.js  
Popper.js came with Bootstrap to make the popovers operation responsive.

* jQuery  
jQuery came with Bootstrap to make some of the components operate in JavaScript.

* Git  
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

* [GitHub](https://github.com/)  
GitHub is used to store the projects code after being pushed from Git.

* [Pixlr](https://pixlr.com/)  
Pixlr was used to resize images and editing photos for the website.

* [Figma](https://www.figma.com/)  
Figma was used to create the wireframes during the design process.

* [Paletton](https://paletton.com/)  
Paletton was used to create a pallette of colours that supported the main colour of the website, which is based on one of the company logos.


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

## Deployment

..........


## Credits

### Code

*  Bootstrap4: Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

### Content

All content was written by the developer.

### Media

All Images are the ownership of Quintain, my employwer.

### Acknowledgements

........

#### Content



#### Media



#### Acknowledgements