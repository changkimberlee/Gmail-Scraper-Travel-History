# gmail_scrape_travelhistory
A tool that scrapes Gmail for flight itineraries to combile your travel history! (A tool I created to help me complete my US citizenship application as a frequent traveler). 

It scrapes my gmail for emails in the past 5 years that contains certain keywords ("flight" AND ("itinerary" OR "reservation" OR "confirmation").  You can edit time range and keywords to fit your need. 

It outputs a CSV that contains the fields: "Email ID", "Subject", "Sender", "Date", "Dates in Body", "Countries in Body", "Airport Codes"


Option for to Authrnticate using temporary access token (Google OAuth 2.0 Playground) or Google Cloud and Workspace
