# Oceanographic Dictionary Web-Application 

This web-app is designed to allow the user to manipulate the data Oceanographic Dictionary records stored in MongoDB. The user is able to create, 
locate, display, edit and delete records in line with CRUD functionality. 

The web-app is easy to use and allows the user to input their own words, categories and definitions into the database. The user can search for 
existing words in the database, as well as display existing and new words. Also, the user is able to edit current words and categories, as well as 
delete them. 

The purpose of the web-app is to ultimately build a large database of Oceanographic words, categories and definitions that will allow people to better 
understand the oceanic environment and all of the associated elements.

The link for the app is: 

*https://ocean-dictionary-flask-mongo.herokuapp.com/*

## UX

In order to make the user experience as easy and enjoyable as possible I opted for a simple looking site that is easy to navigate 
using the navigation bar buttons (Home, Browse Words, New Word and Manage Categories). There is also a search bar within the Navbar 
that the user can type in any word to search, as well as individual letters that are themselves links to all words beginning with the 
selected letter. The user is also able to add a new word using the floating green button to the left of the Navbar, as well as utilise 
links provided in the card placed on the right of the homepage (Words, New Word and Categories). Additionally, there are a selection of 
links in the footer that will assist the user to easily navigate the pages. A paragraph in the center of the Homepage explains what the
web-app is about.

Once the user browses a word using any of the available search facilities, they can then see the category to which that word belongs, as 
well view the drop down definition by pressing the button. There are also button options to edit or delete the word. A warning will present 
it's self to the user if they press the delete button.

To add a word the user is taken to the Add Word page where they can select an appropriate category, input the word and input the definition.
the user then presses the Add Word button to submit the information to the database. The operation can also be cancelled using the cancel button.
Either action will return the user to the Browse Words page that is sorted in alphabetical order.

The Manage Categories page allows the user to view all categories in alphabetical order and then either delete or edit an existing category 
using the buttons provided or add a new Category that will be submitted to the database. If editing the category, the user has the option to 
either save their changes or cancel the operation. Again, if the delete button is pressed a warning message will be displayed. 

The original concepts for the web-app pages can be seen in the *supporting_docs folder* under *wireframe1_oceanic_dictionary_home.png*, 
*wireframe2_ oceanic_dictionary_browse_words.png*, *wireframe3_ oceanic_dictionary_new_word.png* and *wireframe3_ oceanic_dictionary_manage_categories.png*. 
These were created in Balsamiq. There are numerous changes since these  wireframes, mainly due to learning more about the capabilities 
of Python, Flask and MongoDB. There is also a database scehma showing the original idea for the project.

The web-app is aimed at users who share an interest in the ocean and oceanographic words, particularly those who would like to understand 
the spelling or definition of a word, or to which oceanographic category it belongs. 

## Features

### Existing Features

The choice of features, links and buttons available to the user are:

* **Nav Bar –** Contains homepage link in the title of the page that is animated and highlited when the user hovers on it to draw atttention to 
the page title. Below the title is a floating Add Word button which will direct the user to the Add Word page. In the centre of the Navbar is a 
Search bar that the user is able to type any word in to and search the database, this is highlighted by the green search button. The search bar 
will bring up all words related to the specified search that are in the database. The Navbar links that are Home, Browse Words, New Word and Manage 
Categories. Direct the user to these specific pages. The links are hilighted and pulse when they are hovered on to make it clear to the user that they are links.

* **Side Nav Bar –** This becomes available on smaller screen types and is present in the form of the hamburger style menu icon in the top left 
corner of the Navbar. Once the icon is clicked the Side Navbar presents itself with all the links that are hidden in smaller view (e.g. Home, 
Browse Words, New Word and Manage Category) that direct the user to the specified page. The links are highlighted and pulse when hovered on  
to make it clear to the user that they are links.

* **Individual Letter Links –** Each letter of the alphabet is represented by it's upper and lower case character. The individual letters are 
highlighted when hovered over to make the user aaware that they are links. Once clicked the user will be directed to a page that shows all words 
beginning with the specified letter listed in alphabetical order. Form there the user can see the associated category and definition and edit or 
delete the words.


 

### Features left to implement

* Use entire "https://data.opendatasoft.com/explore/dataset/global-shark-attack" data that includes all types of shark and more details.

* Elaborate on Date and Time of day to see if there are any correlations.

* Connect dashboard directly to API. This was originally attempted, but proved too unmanageable when it came to trying to keep the dashboard looking simple.

## Technologies Used
The languages, frameworks, libraries and other tools utilised for building this data dashboard are:

*	**HTML 5 -** The dashboard uses HTML5 as a fundamental basis for building the dashboard. Where possible semantic HTML is used to give the viewer a better understanding.

*	**CSS3 -** The dashboard uses CSS3 for styling of all elements within the website. It is linked from the page to the *style.css* file and is used for all content, including such as layout of colours, navbar, background, images etc.

*	**Bootstrap 3.7.6. -** The open-source Bootstrap framework has been used to implement the layout of the dashboard. Bootstrap is also utilised to accommodate the responsive and mobile first design of the dashboard. https://getbootstrap.com/

* **JavaScript -** The dashboard uses Javascript to provide dynamic interactivity, as it is a full-fledged versatile programming language.

* **jQuery -** The dashboard uses jQuery, as it simplifies a lot of complicated tasks from JavaScript, such as AJAX calls and DOM manipulation. jquery.com/jquery-3.4.1

* **Crossfilter -** The graphs and charts on the dashboard are all linked using crossfilter, which manages the data behind the graphs and charts, allowing interaction with coordinated views and functioning. It synchronises all the charts when used.

* **DC.js -** The dashboard uses DC.js for data visualisation and analysis. 

* **D3.js -** The D3.js library allows manipulation of elements on the dashboard in the context of the dataset.

*	**Cloud9 AWS (Amazon) -** Cloud9, a cloud-based integrated development environment (IDE) that has been used to write, run, and debug the code used for the dashboard. https://c9.io/rsimons

*	**GitHub -** GitHub has been used for version control of the code by using Git functions in the control panel. Github was utilised frequently during the development of the dashboard.  https://github.com/

*	**Google Fonts-** The dashboard uses Google fonts to accentuate certain text. https://fonts.google.com/

## Testing

Various methods of testing have been carried out to test the code of the dashboard. Continuous testing throughout the development has been implemented to check the quality of the code. 
The aim is to check the functionality of the code on different devices (mobile, tablet, desktop) with an overall perspective of responsive and mobile first design.
The site has been viewed and tested in **Firefox**, **Safari**, **Chrome** **Microsoft Edge** and **Explorer**. The devices used to test the site are **iPhone 5/SE**, **Samsung Galaxy**, 
**iPad**, **iPad Pro** **iPhone X**, **iPhone 6/7/8**, **Pixel 2**, **Pixel 2 XL** **Hudle2** and **Samsung laptop**. 

The final desktop wireframe for the dashboard can be seen in the *supporting_docs folder* under *wireframe2_global_white_shark_attacks.png* and this was used initially to plan the dashboard and build around. 
The opinions of numerous people including chat forums were asked in the final stages of the project.

The main basic functions of the dashboard that required rigorous testing in different scenarios are listed below.

*	**Main Navigation** 
    * Hover mouse over all graphs and charts to ensure that they show the count of that particular section. Every pie-chart section and bar  or line should 
      function in this way.
    * Refresh chart buttons were tested to ensure that the user can refresh the page and where possible is returned to the nearest location that they were previously analysing.
    * Table `Last` and `Next` buttons were rigorously tested to ensure that they function correctly.
    * Once clicked the section of each graph or chart should be highlighted and all other graphs and charts and the table should conform and adjust to 
      to this selection. This feature was heavily tested so that the user can analyse specific information easily.
    * All of the drop down selectors were thoroughly tested so that they diplay the correct information.

*	**Responsive / Mobile First design** 
    * The dashboard page has a **Header**; **Main Section** and **Footer**. These needed to display correctly accross 
      all devices and screen resolutions. primarily checks are required to ensure that the dashboard collapses in to columns in mobile view 
      and that the information is presented in a clear and legible fashion.
    * The header image and title was removed in mobile view in order to have the Nav Bar at the top of the page. This was done to provide a 
      better user experience and clarity of design, as the image did not show well in a smaller view. 
    * The table was removed in mobile view as it did not present well in this view and the data was too small if the table is shrunk. 
      All of the data available in the table is also available in the graphs and charts.
    * The second paragraph was removed in tablet view, as this utilised too much space and did not present well in tablet view.

*	**Data** 
    * The data used for the dashboard was exported from https://data.opendatasoft.com/explore/dataset/global-shark-attack%40public-us/export/, 
      which also had the option of connecting directly to the API https://data.opendatasoft.com/explore/dataset/global-shark-attack%40public-us/api/, 
      but this proved unmanageable due to the variations of spellings, capitalisation, size and non-uniformity of the data set. I decided to instead 
      export the .csv file that was more manageable for the simplified data that I wanted to present. 

## Issue List



  | Issue  |                 Description                     |       Solution                      |  
  | ------ |:-----------------------------------------------:|:-----------------------------------:|
  |   1    |Attempted to connect dashboard directly to API but data proving unmanageable|Downloaded .csv file instead|
  |   2    |Unable to download export whole dataset due to issue with website |downloaded each year separately|
  |   3    |Issues with uniformity of the .csv data (e.g. spellings and capitalisation) |Amended these issues directly in .csv file|
  |   4    |Composite chart , Stacked bar chart and Bar graph not scaling correctly on smaller devices |Used viewbox resize to scale correctly |
  |   5    |Dates on Composite Chart X-axis displaying incorrectly (e.g. 1,985)|Function added to bottom of `show_country_year`  to correct this |
  |   6    |Attempted to use Age Range function that would separate the ages Pie Chart into ranges |This did not connect to other charts. Added Age range column to .csv file |
  |   7    |Queue, Crossfilter and and DC.js showing as ‘Undefined’ in main.js tab | `/*global varname*/` added to remove undefined variable errors |
  |   8    |Header image and title took up too much space in responsive views | Changed display to none in media query below tablet resolution |
  |   9    |”Next” and “Last” buttons did not work on Table |Event listener added to these buttons to globally rectify this |
  |   10   |Explorer displaying the charts which use viewbox resizing too small |Decided to leave this, as browser being phased out and rarely used |
  |   11   |Second intro paragraph did not fit on tablet size and was left in row alone | Removed from tablet view using media query |
  |   12   |Stacked bar chart did not read well when using percentages to diplay types of attacks that were fatal |Opted to use actual count as this was clearer|
  |   13   |Table not scaling correctly on smaller devices |Used media query to remove table from smaller devices |
  |   14   |Needed to validate CSS for debugging purposes | Utilised jigsaw.W3 CSS Validator (zero errors) |
  |   15   |Needed to validate JavaScript for debugging purposes | Utilised jshint.com (no errors) |
  |   16   |Needed to validate HTML for debugging purposes | Utilised W3 Markup Validation Service (1 warning) |
  |   17   |HTML Validation warning "Section lacks heading" | This warning can be ignored as does not affect code |
  |   18   |X-axis titles on Activities bar graph not displaying correctly in horizontal view |Used `text-anchor: end !important` in CSS to angle text |
  |   19   |Data in .csv file was causing more columns in graphs for the same variable (e.g. Body Boarding and Boogie Boarding) | Amended to .cvs variable names to make more uniform |
  |   20   |Header `Refresh Charts` button was not positioning correctly in Windows Edge | Used `float: inherit` in CSS to fix |
  |   21   |Is HTML semantic and self explanatory  | Added further comments to index.html file |
  |   22   |Is main.js self explanatory  | Added further comments to main.js file |

  
## Deployment

The dashboard is designed in the AWS Cloud9 environment and regularly committed and to GitHub after each crucial piece of coding. Using this method as a sanity check 
for the development enabled me to restore the site back to previous stages when it functioned correctly or easily find lost pieces of code. 

To deploy the project to Github the following steps were taken:

  1. created a `master` branch in Github repository 
  2. Used Local AWS Cloud9 environment used to build the site
  3. Committed files to the staging area using bash terminal commands: `git status`; `git add (specify directory)`; `git commit -m"add message"`
  4. Pushed files to the working environment using `git push`, which then updates the repository and is also viewable as a link https://github.com/RobSimons1/global-white-shark-attack-dashboard for testing on other devices and screen resolutions
  5. Published site from `master` branch using `settings` tab in the main page of the repository, select `source` as `master branch`, then `save`
  6. The repository can be cloned by clicking `Clone or Download` on the main page of the repository 
  7. In the Clone with HTTPs section, click the clipboard icon to copy the clone URL for the repository
  8. Open Git Bash Terminal
  9. Type `git clone`, and then paste the URL
  10. Press `Enter`. A local clone will be created.

## Credits 

### Content

This README.md file is based on the Code Institute template.

### Media 

CBS Interactive Inc.(2019): https://www.cbsnews.com/pictures/five-most-dangerous-sharks-to-humans/

Data obtained from: https://data.opendatasoft.com/explore/dataset/global-shark-attack%40public-us/export/

Dataset info for global-shark-attack@public-us; http://www.sharkattackfile.net/incidentlog.htm

Favicon image downloaded from: https://www.shutterstock.com/image-vector/dangerous-sea-life-207907852?studio=1

Favicon – created using http://www.favicomatic.com/done

Shark and Surfer Image: https://usatunofficial.files.wordpress.com/2011/10/shark-in-a-wave-with-surfer.jpg

### Acknowledgments

Thank you to the Carcharodon Carcharias (White Shark) species whom I find so intriguing and awesome and the people at sharkattackfile.net for compiling such a 
huge and detailed dataset. I would like to thank Anthony Ngene (https://github.com/tonymontaro) for his invaluable feedback, as supervisor for this project. 