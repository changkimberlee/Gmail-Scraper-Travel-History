# gmail_scrape_travelhistory
This is a quick little tool that scrapes Gmail for flight itineraries to compile a travel history when the I-94 was unable to locate my history. I created this to help complete my US citizenship application, which requires you to list the past 5 years of travel history abroad. As a frequent traveler (worked in international development) this was extremely hard to recall (let alone list accurately for a naturalization app)! 

This tool scrapes my Gmail for emails in the past 5 years that contains certain keywords (("flight" OR "trip" OR "booking) AND ("itinerary" OR "reservation" OR "confirmation").  You can edit time range and keywords to fit your need (Search "EDIT HERE" to find the lines to edit). 

It outputs a CSV called "email_output.csv" that contains the following fields: "Email ID", "Subject", "Sender" (Email Address), "Date", "Dates in Body", "Countries in Body", "Airport Codes". This spreadsheet can help you sift through your memory easier and get the exact dates of travel.

Option for to authenticate using temporary access token (Google OAuth 2.0 Playground), or Google Cloud and Google Workspace accounts
