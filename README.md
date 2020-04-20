# Budget Tracker

## See it live: [Click here](https://dollar-watcher.herokuapp.com/)

A budget tracking application with offline capability.

A user can document expenses and deposits in their budget with or without a connection. During offline use, transaction data is temporarily stored with IndexDB and pushed to the main database when brought back online. 

Offline Functionality:

  * Enter deposits

  * Enter expenses

When brought back online:

  * Offline entries are added to tracker.

# Technologies Used:

Manifest
Service-Worker
IndexDB