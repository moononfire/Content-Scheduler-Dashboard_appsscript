# Share-Nurture-Dashboard_appsscript

#### Isha Share&Nurture Project

Share&Nurture is a project by a few volunteers from the Isha Foundation, which aims at sharing content related to yoga, health & wellbeing.

During the Share&Nurture project many bitly links are created. This code powers the Google spreadsheet in which all created bitly links are stored. Making it possible to fetch data from Bitly API and update the database with  

#### spreadsheet
Link do the "Dashboard Data" SPREADSHEET: https://docs.google.com/spreadsheets/d/1F8zPtmY9enT7HVzgH6aJFlFGftjTOGupRxqsaTONezQ/edit#gid=555494322

#### script
Link to the "Dashboard Data" script: https://script.google.com/home/projects/1WUe1SWFkHqq1n9jb3hdeFd47C-_izeP0DASjPxJV1FRtib7M2QK-vNRI/edit

### How it works
For every bitly link stored in the spreadsheet, the click count on the bitly link is updated by being fetched from Bitly API (only for bitlinks younger than 30 days).
To start the function go in the top menu under Isha Tools > Fetch Bitly API Data. An API call is made for each bitly link, making a request to get the number of clicks on this bitly, and updates the value.
This data is later used in a Google Data Studio project to better visualize the clickrates for each country. Link to the "Dashboard" file: (to be added...)
