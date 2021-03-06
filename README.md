## Physician Finder <hr>

Find the geographical location of a physician by inputing their full name into this application!

## How it Works <hr>

Using the 2016 CMS dataset of physicians, this applications uses the Google Maps GeoCode API to calculate the coordinates from the address of each search query.  These coordinates are then used to render markers a map generated by the Google Maps React node module.

## Tech/Framework Used <hr>

React, Node.js, Express, MongoDB, Google Maps API,

## Installation <hr>

1. Clone repo into project folder
2. Run `npm i` in both the root and `client` folder to install all dependencies.
3. Use this [Link](https://www.cms.gov/openpayments/explore-the-data/dataset-downloads.html) to download any dataset of your choice from the CMS website.
4. In created a MongoDB database called "physicianFinder_DB" and a collection called "physicianData".
5. Run `nodemon server.js` in the root directory and `npm start` in the client folder to start the app.


## Feel Free to message me with any questions!
