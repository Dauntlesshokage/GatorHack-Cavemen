## Inspiration
We wanted to create something that everybody can use easily(hence the name cavemen). Our inspiration is to cut down the navigation time in the website by giving the control to the AI bot. This makes the user experience smooth and find the information easily.

## What it does
It scraped the entire verizon website for data and we used a JSON parser to make a JSON file. With the JSON file fed into the ChatGPT LLM with custom data

## How we built it
We made a JSON scraper and scraped the Verizon website. We fed the data into LangChain LLM to create a custom AI bot that has all info about verizon products. We made a Flask web app that communicates with the bot at the backend that can be accessed through the Verizon front end and take data from it.

## Challenges we ran into

All the technologies that we used in this project are something we never used before. We never used the Flask web framework and also never worked with the OpenAI API. As beginners it was very challenging.

## Accomplishments that we're proud of

Creating a wroking model at the end after the long hustle.

## What we learned
We learned a lot about building REST APIs and Flask framework. We also learned about OpenAI API and how it can be leveraged to do a lot of amazing projects.

## What's next for Cavemen

Make it mobile responsive and build a more exotic UI and also make a database to save all the previous queries to re-feed it into the bot for better responses.

[Demo video](https://youtu.be/6WMk-FjZ4KI)
