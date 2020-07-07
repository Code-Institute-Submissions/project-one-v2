## Steps taken in development

**1. Set up pages file structure required, including assets / css / image**

* 'index.html' will remain as main page, ie 'Overview'

**2. Set up page structure in index.html**  
  * Bootstrap  
  * Fonts  
  * Fontawesome
  * Google Fonts
  * Body outline  
    1. Header - to include logos and naviagation bar
    2. Section - to include main page content (to be divided by Bootrap into information 'zones')
    3. Footer - Concept on what this is to include to be developed at later date  

**3. Header - Logo banner**

  * Utilised two logos as header banner in a horizontal line
  * Resized images so that they were the same height
    *  *Is there a way to easily adjust image sizes within CSS?  Struggled to maintain ratio when increasing height.*
    *  *What is the best way to automatically adjust sizes?  Set container or row height?*

**4. Navigation Bar**

  * Layout for large screens - utilised Bootstrap grid layout system for navigation bar, hidden on XS and S screens.
  * Layout for small screens - utilised Bootstrap Dropdown, hidden for MD+ screens
    *  Adjusted default formatting to match brand for both large and small screens of Naviation Bar
  * Integrated **hover** over the nav links on the large screen layout to show image of the project
    * Utilised animation to slide-down opaque version of an image representing the project
    *  *Challenge to locate image directly below menu name, but overcame.*
    *  *Would prefer the image to respond to screen size but found this difficult in conjunction with @keyframes*
  * Future improvements?
    *  *May consider opting for Bootstrap Navbar in future, as this would accommodate screen size changes more easily, but decided to leave for this project in order that **hover** would work on the large screens.*

**5. Main Section - Overview and Grapth**

  * Container split into two sections, wrap on XS and S screens to maintain equal / central components
  * Overview to 
