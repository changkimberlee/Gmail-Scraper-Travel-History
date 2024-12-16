# gmail_scrape_travelhistory
This is a quick little tool (and Python + Jupyter Notebook practice) that scrapes Gmail for flight itineraries to combile your travel history! I created this to help me complete my US citizenship application, which required you to list the past 5 years of travel history abroud. As a frequent traveler this was extremely hard to recall (let alone accurately for a naturalization app)! 

This tool scrapes my gmail for emails in the past 5 years that contains certain keywords ("flight" AND ("itinerary" OR "reservation" OR "confirmation").  You can edit time range and keywords to fit your need (Search "EDIT HERE"). 

It outputs a CSV called "email_output.csv" that contains the following fields: "Email ID", "Subject", "Sender" (Email Address), "Date", "Dates in Body", "Countries in Body", "Airport Codes". This spreadsheet can help you sift through your memory easier and get the exact dates of travel.

Option for to authenticate using temporary access token (Google OAuth 2.0 Playground), or Google Cloud and Google Workspace accounts
