# MailChimp-API-Collecting-List-of-new-subscribers-using-Node.js
Record lists of audience  from the node.Js application by using Mailchimp API.

### Backend: Node.js and Express on the backend;
### Frontend: HTML, CSS and Bootstrap  on the frontend.
The emails are saved to Mailchimp using the Mailchimp API.

Hosted on Heroku: https://dry-island-62604.herokuapp.com/

## Install and Setup
### Install node modules:

$ npm install

You will need a Mailchimp account API Key, server location and audience list ID, so you need to sign up: https://mailchimp.com

To create a new API Key, click on your user -> Account -> Extras -> Create a Key

To get your audience list ID, click on Audience -> Audience Dashboard -> Settings -> Scroll to the bottom where it says Unique id for audience ...

To get the Mailchimp server ID, check your API Key, and it is the last 4 chars, for example your key is sslkflskdfjsfowiejflskdfjus14. The server ID is us14. The server number could be a single digit, for example us4.

Create a .env file in the main directory and add your id and url in it.

Run

$ npm start

