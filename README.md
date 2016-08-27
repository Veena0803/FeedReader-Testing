# Feed Reader Jasmine Testing

### Description
This project aims in learning testing using Jasmine framework.

#### Getting Started
  - Clone the repository
  - Open index.html in the browser
  - Click on the various links to visit the website
  - Toggle menu icon to open or close the menu
  - Click on menu items to select different topics.
  
#### Structure of the project
  - Function logic is in the app.js file
  - test suites are in the feedreader.js

#### Suites Include:
- RSS Feeds
    - are defined
    - each feed has a URL defined
    - each feed has a name defined
- The Menu
    - menu is hidden by default
    - should toggle side menu when menu icon is clicked
- Initial Entries
    - after the loadfeed function is called & executed, there is atleast a single .entry element within the .feed container
- New Feed Selection
    - when a new feed is loaded, the content changes.

#### Stuff used to make this
- [jasmine](http://jasmine.github.io/2.2/introduction.html) for jasmine documentation
- [YouTube](https://www.youtube.com/watch?v=_cLvpJY2deo) to learn jasmine basics.