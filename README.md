** This is an unfinished project based on truffle webpack box, "approveLoan" function, loaner/borrower
   ArrayList of the smart contract and the front-end is incomplete

** In order to run the project, please follow the following steps:
   1. Make sure you have truffle, metamask, npm and Ganache(optional) installed and updated
   2. unzip the file to the directory you like
   3. Open commandline/terminal and go to the directory where the file is unzipped
   4. Start Ganache, it will deploy a test network at local port 7545 automatically
   5. Enter "truffle compile"
   6. Enter "truffle migrate", the contract should be deployed at port 7545 now, if you wish to change that,
   please edit the file "truffle.js"
   7. Open a new commandLine/termnial and enter "npm run dev", the front end should be listening at port 8080
   8. go to your browser and go to "http://localhost:8080/"
   9. You can start from clicking "request loan" as a borrower now, since "approve" function is unfinished, it
   will only add your debt
   10. You can pay your debt by entering amount and address that you wish to pay to, this part will be removed
   after the "approve" function is finished and only the "pay 10 UNI each time" will actually work according to
   the "get_started" document

** It's an unfinished project and I'm not satisfied with it
** If it's possible please give me the contact of your developer so I can ask him questions
