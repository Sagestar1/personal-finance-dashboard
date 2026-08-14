# personal-finance-dashboard
Welcome to your financial dashboard! You can download your own file to privately start recording income, expenses and transfers, categorize their spending, track savings goals, and view both monthly and yearly financial summaries now. Designed with young adults in mind who balance rent, groceries, transportation, school costs, and entertainment. 

Finances Draft August

Features: 
`Add and categorize income, expenses, and transfers
`Track monthly income and total expenses
`Automatically calculate net cash flow
`Calculate monthly and annual savings rates
`View spending by category with a color-coded pie chart
`Track a customizable savings goal
`View annual income, expenses, and net cash flow
`Calculate average monthly spending for each year
`Identify the highest-spending month
`Identify the largest annual expense category
`Switch between the current year and previous years
`Export transaction data as a CSV file
`Store financial data locally in the browser
`Clear stored data and start over
`Responsive interface for different screen sizes
`Tech Stack

HTML5 — page structure and application interface

CSS3 — responsive layout, custom styling, and visual design

JavaScript — transaction management, calculations, filtering, and interactive features

HTML Canvas API — spending-category pie chart

Web Storage API (localStorage) — saves transaction and savings-goal data in the user's browser

CSV Export — allows transaction data to be downloaded for use in spreadsheet software

Privacy & Data Storage

This application does not upload, transmit, or publish the financial information entered by users. Transaction and savings-goal data are stored locally in the user's own browser using the Web Storage API (localStorage).

There is no user account system, server, cloud database, or developer dashboard connected to this version of the application. As a result, the developer cannot view or access the financial data users enter into the app.

Data remains available only within the browser/profile where it was entered and can be removed using the app's Clear data feature or by clearing the browser's site data.

Important: Because the data is stored locally in the browser rather than protected by a user login, anyone who has access to the same device and browser profile may potentially view the locally stored data. Users should avoid entering sensitive financial credentials such as bank account numbers, card numbers, passwords, or Social Security numbers.

How to Run

Download or clone the project repository.

Open the project folder.

Open index.html in a modern web browser.

The application will run locally without requiring any additional installation.

You can select Load demo data to populate the dashboard with sample transactions and explore the monthly and yearly analytics.

Because the project uses browser localStorage, information entered into the dashboard remains saved in that browser until the user clears it.
