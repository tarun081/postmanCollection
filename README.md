
Problem : There should be  a central place where  all the postman collections should available with latest changes for free accounts via CLI . So we need some utility that can help in Back Up and Sync Your Postman Collections to Bitbucket .

Solution : We have created few scripts that will solve this problem for free accounts . 

Following are the features of this utility :

We are using GIT so it will provide all the benefits of VCS . like :- we can track the Bitbucket changes , we can create separate branches etc . 
Download all collections from personal and team workspaces
Backup all available collections  .
Use multiple API keys to handle all your Postman accounts .
Works for Free Postman accounts

One time SetUp  Details :

Clone repo  
cd postmansync
npm install
Generate API Key with name X-API-KEY ( Navigate to Postman Integrations Dashboard ) 




5. Set up your API key into config.json
