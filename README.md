# Project Overview

This project adds unit tests to feed reader application using [Jasmine Framework](https://jasmine.github.io/index.html). The test are written in the [feedreader.js file](jasmine/spec/feedreader.js)

## Running the Project?

1. Clone this github repository
2. cd into the repository
3. Open index.html using a browser

This project can also found [here](http://pranavjain.info/frontend-nanodegree-feedreader/)



# Tests Added

1. RSS Feeds Data Validation tests
    - allfeeds array is defined and has at least one element
    - each item in allfeeds array has a name
    - each item in allfeeds array has a url
2. Menu tests
    - menu is closed by default
    - menu's visibility is toggled when icon is clicked
3. Initial Entries tests
    - initial feed data has at least one entry
4. New Feed Selection tests
    - when a new feed is loaded by the `loadFeed` function that the content actually changes
