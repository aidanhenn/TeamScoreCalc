# Track and Field Conference Score Predictor App

This app is a JavaScript-based web application that utilizes the Puppeteer webscraper and Express framework for the frontend. 
The purpose of the app is to provide users with predicted conference scores for each team based on their previous results. 
This app works for any conference in America on the TFRRS website.

## How to Use

To use the app, input the URL of the track conference you want to scrape from the TFFRS website in the provided text box and click the submit button. 
The app then scrapes the performance list of the conference and calculates the predicted scores for each team based on the scoring method of 
10 points for 1st place, 8 points for 2nd place, 6 points for 3rd place, 4 points for 4th place, 2 points for 5th place, and 1 point for 6th place.
To find a valid URL to webscrape, go to the TFFRS website and find a conference's performance list. 
For example, here is the Big 12's 2022 outdoor performance list: https://www.tfrrs.org/lists/3847/Pac_12_Outdoor_Performance_List.


## Installation

To install and run the app, follow these steps:

1. Clone the repository to your local machine.
2. Install the required packages by running npm install. (Install Puppeteer and Express)
3. Run the app by running npm start.
4. Access the app through a web browser by navigating to http://localhost:3000. (Also available to try out on my website aidanhennessy.com)

## Future Development

The app is still in its early stages and there are a few things I plan to add in the future. These include:

- A feature to allow users to input their own scoring method
- Improved UI design
- Option to choose which gender to score (currently only mens scores are displayed but you can score womens teams instead by chaning the gender variable from "M" to "F") 
