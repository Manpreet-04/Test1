**//
Design (40 marks). Things to consider: 
What are the key elements for this application?How would you manage these?
The key elements for this application include creating and managing customer accounts, allowing for deposits and withdrawals, and providing account balance information.
To manage these elements, I would create classes for customers, accounts, and transactions. The customer class would store personal information such as name and contact details, while the account class would store information such as account balance and transaction history. The transaction class would store information such as the amount, type (deposit or withdrawal), and date of the transaction.
Is a state-managed solution appropriate here?Should you be considering JAM or MVC?
A state-managed solution would be appropriate for this application, as it would allow the user to securely log in to their account and view their data without having to re-enter their credentials every time. A Model-View-Controller (MVC) architecture would be the best choice for this application, as it would provide a structured framework for the application to be built upon.
Intelligence Choices
For this application, a full-stack tool stack would be the best choice. A JavaScript library such as React.js could be used for the front-end, with a Node.js server for the back-end. A database such as MongoDB could be used to store and manage the user data. A library such as Passport.js could be used for the user authentication and authorization.
Implementation:
The first step in implementing this application would be to set up the necessary infrastructure for the application. This would include setting up the web server, database, and other necessary services.
The next step would be to create the user authentication system. This would involve creating a user login page, a user profile page, and a password reset page. The user profile page would also allow the user to update their account information and settings.
Once the user authentication system is set up, the application can be built. A form would be created for the deposit and withdrawal page, which would allow the user to enter the amount they wish to deposit or withdraw. The account balance page would display the user's current balance.
Finally, the application would be tested and deployed. This would involve testing the user authentication system, the deposit and withdrawal forms, and the account balance page. Once the application is tested and ready to be deployed, it can be deployed to a web server and made available to the public.
//**