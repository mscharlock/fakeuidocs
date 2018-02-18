# A Thing: Contentful UI Extension

## Description
I bet you've always wanted a tool that [does a thing on Contentful]. Our team developed a great solution so that you can do just that!  

## Features
[Insert blurb about the great features this tool offers]

## Pre-Requisitions to Installation
Because the most convenient way to upload and manage extensions in Contentful is through their CLI, make sure you have installed their command line interface tool (CLI).

Install it using npm:
```
npm install -g contentful-cli
```
Now, configure your .env file with your SPACE_ID and CONTENTFUL_MANAGEMENT_ACCESS_TOKEN.

⭐️ Wait...where are those, again? Your SPACE_ID can be found in Space Settings > General Settings on Contentful's Web App and the CMA Token can be found in Space Settings > API Keys. If you need to create a CMA Token, find out how to do that ![here](https://www.contentful.com/developers/docs/references/authentication/#getting-an-oauth-token).

## Installation
1. Clone this repository
2. `npm install` dependencies
3.

## Register this Extension in Your Space
Now, register this extension with contentful through the CLI using the following command:
 ```npm run create
 ```
 Once your extension is registered, you'll be able to see the extension as an option under settings > appearance on any content with the type of text.

To run your extension locally, run the following in the CLI:
```
npm install -g http-server   //this installs the http-server dependency globally
http-server -p 3000          //sets our server at http://localhost:3000
npm run lhost
```

If you want to deploy the code from app.html directly again, without having to serve it locally, you can run the following in the CL:
```
npm run update
```

⭐️Looking for more information on Contentful UI Extensions? Check out the documentation ![here](https://www.contentful.com/developers/docs/references/content-management-api/#/reference/ui-extensions).
