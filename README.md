# Retrieve all code scan results in a csv file as a report

### Running the script
1. Clone this repo to your local machine
2. Create a file called .env 
3. Create a [GitHub Token](https://github.com/settings/tokens) , add it to your github secrets, which has the `repo` > `security_events` permission. (`repo` permission is needed for private repo)
4. Add the token to your .env file as shown `GH_AUTH_TOKEN=secrets.TOKEN`
5. Run `npm install` to install node dependencies
6. Run `node get-code-scanning-alerts.js Havod-Technologies > report.csv` where `Havod-Technologies` is the name of your target org. Note, if SSO is enabled on your org, you will need to SSO enable your token

### License
This project is licensed under the MIT License. 
