# Newsletter Signup Web Application

This is a simple newsletter sign-up web application built with Node.js and Express.js. It uses Mailchimp API to add subscribers to a specific audience in Mailchimp. Hosted on Heroku.

## Installation 

To run this application locally you need to:
- Clone this repository or download the zip file.
- Install the dependencies by running 'npm install'.
- Add your MailChimp APIKey and List ID.

## Usage

After installing and running the application, you can access the homepage at http://localhost:3000. The homepage contains a simple form that asks for the user's first name, last name, and email address.

Once the user submits the form, the server sends a POST request to Mailchimp API to add the user to the specified audience. If the request is successful, the user will see a success page. Otherwise, they will see a failure page.

## Technologies

- Node.JS
- Express.JS
- MailChimp API
- Hosted on Heroku
