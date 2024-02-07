# Assignment 2 - EcoInvest - MIST 353 Spring 24

## Introduction
This README file provides an overview of my Assignment 2 for the MIST 353 Spring 2024. The assignment involves the development of a website that pulls in stock data of companies and compares it against climate data. Several websites and 1 API have been identified for potential use in this project, and two GitHub repositories are highlighted as sources of valuable resources.

## Current Phase
This project is in the prototype/ babystep phase. I am currently building out the basics of the web app. I currently have the landing page, an information page, registration page, and login page. However, the functionality of the last two hasn't been implented yet since we have added databases to our learning.

### Landing Page/ Index.cshtml
My landing page is fairly simply right now. I have added some sections and paragraphs with text and links to other current pages. I also added some custom JS to prompt the user to enter an email address when clicking the "Join Our Newsletter" button.

### Information.cshtml
This page is very basic for now. Moving forward I want this page to be the main area for users to get the information they want. I want to add a search functionality to allow users to find the companies they want. Also a filter function to allow the user to find companies based on multiple criteria.
I also want to expand on the table in this page. I want to include a sparkline for each company that shows the compared climate and stock data of each company.
I want to link each company on the information page to a more detailed information page for that specific company and more functionalities to selecting date ranges, switching the type of charts shown, and more.

### Register/Login Pages
These pages are just placeholders until the class progresses far enough to incorporate databases into the project. Then I will be able to store the user accounts and users can login with their accounts or create new ones.

# Research

## Website 1: Robinhood
- Website URL: [Robinhood](https://robinhood.com/us/en/)
- I would like to pull in stock data of companies and compare it against climate data. I chose Robinhood as one of my sites because they are well known in investing. I also noticed the use of smaller charts that show 1 day stock price changes and I want to use these to show the data of stock prices against climate data.  I also want to include a way for people to sign up for an account or sign into their account. 
- Description: Robinhood is a well-known platform for investing in stocks. The website provides real-time stock data, including 1-day stock price changes.
- Project Use: This website will be used to fetch stock data for analysis and display it in conjunction with climate data. Additionally, it may be used to incorporate user account functionality.

## Website 2: Coinbase
- Website URL: [Coinbase](https://www.coinbase.com/)
- I chose Coinbase because there is a change that I might want to potentially include cryptocurrency into the site. Like with Robinhood, Coinbase is well known for buying, selling, and trading cryptocurrencies. I might also want to incorporate an API for crypto data.
- Description: Coinbase is a popular platform for buying, selling, and trading cryptocurrencies. It offers a variety of cryptocurrencies for trading.
- Project Use: Coinbase may be considered for potential inclusion of cryptocurrency data into the project. The website also provides APIs for crypto data integration. However, these cost money. I might use their API if I plan on developing this application.

## Website 3: Green America
- Website URL: [Green America](https://www.greenamerica.org/)
- Green America is a leading nonprofit organization that focuses on sustainability and ethical business practices. While investigating their website I did not notice any bootstrap, but perhaps I missed it. I also noticed the use of many classes and id. A few things I want to incorporate into my website would be a collapsable menu with hyperlinks to more pages of the website and maybe linked images to more information or articles and potentially a search bar. They used many things that I am not aware of but that also gives me many things to research and potentially use.
- Description: Green America is a leading nonprofit organization focused on sustainability and ethical business practices. The website may contain valuable design and functionality elements.
- Project Use: Inspiration may be drawn from Green America's website, such as collapsible menus with hyperlinks, linked images for additional information, articles, and a search bar.

## API 1: Alpha Vantage - Stock API
- API URL: [Alpha Vantage Stock API](https://www.alphavantage.co/)
- Documentation: [Alpha Vantage API Documentation](https://www.alphavantage.co/documentation/#intraday)
- Description: Alpha Vantage offers a free stock API that provides stock market data for analysis, including intraday data.
- Project Use: The Alpha Vantage Stock API will be used for fetching stock data for analysis alongside climate data.

## Repositories

### Repo 1: Web Development Resources
- GitHub Repo URL: [Web Development Resources](https://github.com/markodenic/web-development-resources/tree/main)
- Description: This GitHub repository contains a wealth of links to web development resources, documentation, and other useful information.
- Project Use: This repository serves as a valuable resource for additional information and learning materials related to web development.

### Repo 2: Semiotic
- GitHub Repo URL: [Semiotic](https://github.com/nteract/semiotic)
- Description: The Semiotic repository focuses on data visualization, which will be essential for displaying stock and climate data on the project's website.
- Project Use: This repository provides insights and tools for effective data visualization within the project.

## Additional Future Enhancements
- Include a logo. I have already had ChatGPT create some logos. I plan on picking on for this project and implement it throughout the web app.
- I have included additional enhancements for my already created web pages above.

## Conclusion
This README.md file outlines the key websites, APIs, and GitHub repositories identified for Assignment 2 in the MIST 353 course. These resources will be essential for the development of a website that compares stock data with climate data and potentially incorporates cryptocurrency data. The repositories mentioned offer valuable information and tools to aid in the project's development and data visualization.

## Citations
- W3Schools: (https://www.w3schools.com/)
- Bootswatch: (https://bootswatch.com/)

- ChatGPT Prompts:
- JavaScript Newsletter Button:
- give me a custom javascript that when someone clicks on a button it asks them to enter there email to join a newsletter

- Custom CSS Buttom
- give me custom css for a button that changes from white to green when you hover your cursor over it
- I did change a few things that ChatGPT did. I changed the colors slightly and changed the transition time from 0.3 to 0.5s.
