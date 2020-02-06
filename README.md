# online-offline-budgeteer

## Overview

This simple transaction application tracks deposits and withdrawls of funds, online and offline.

### Functionality

The UI is fairly simple: users can create transactions with names and amounts, and click buttons that will either add or subtract the inputed amount. A list of all transaction is displayed, as well as a graph displaying the transaction history. This application uses MongoDB to store transactions. 

### Offline Functionality

Using a Service-Worker and indexedDB, this application can work when the user is offline as well: when an offline transaction is entered, the information is cached to the indexedDB and added to the MongoDB when the user return online.

### Technologies Used

This application uses Node.js, an Express server, MongoDB with Mongoose, API calls, and indexedDB.

### Deployed

https://gentle-meadow-93413.herokuapp.com/
