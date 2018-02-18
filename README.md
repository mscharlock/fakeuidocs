# Thing: A Contentful UI Extension
[A header image of some sort, maybe a logo for "Thing"]

## Description
I bet you've always wanted a tool that [does a thing on Contentful's Web App]. Our team developed a great solution so that you can do just that!  

## Features
[Insert blurb about what thing offers, highlighting a specific use case to show usefulness for developers]. Thing offers:
- [a feature]
- [another feature]
- [yet another great feature]

## Sample JSON Object and/or Sample Screenshot
Using [Thing], you'll be able to create content that looks like this:
```
{
//sample JSON
}
```
(Or, alternatively, I would post some kind of screenshot here to illustrate whatever it is that Thing adds/extends)

## Pre-Requisites to Installation
Because the most convenient way to upload and manage extensions in Contentful is through their CLI, make sure you have installed their command line interface tool (CLI).

Install it using npm:
```
npm install -g contentful-cli
```
Now, configure your .env file with your SPACE_ID and CONTENTFUL_MANAGEMENT_ACCESS_TOKEN.

⭐️ Wait...where are those, again? Your SPACE_ID can be found in Space Settings > General Settings on Contentful's Web App and the CMA Token can be found in Space Settings > API Keys. If you need to create a CMA Token, find out how to do that [here](https://www.contentful.com/developers/docs/references/authentication/#getting-an-oauth-token).

## Basics of Installation
1. Clone this repository
2. `npm install` dependencies
3. Register the extension in order to use it (see below for instructions)
4. Use extension in Contently's Web App by selecting any content with a type of "text" and selecting [THING] under Settings > Appearance.

## Register this Extension
Now, register this extension with contentful through the CLI using the following command:
 `npm run create`

 Once your extension is registered, you'll be able to see the extension as an option under settings > appearance on any content with the type of text.

To run your extension locally, run the following in the CLI:
```
npm install -g http-server   //this installs the http-server dependency globally
http-server -p 3000          //sets our server at http://localhost:3000
npm run lhost
```
⭐️ Note: since Contentful runs in an HTTPS environment, running http://localhost:3000 will mean you will have to "Load unsafe scripts" in Chrome (or other browser of your choice).

If you want to deploy the code from app.html directly again, without having to serve it locally, you can run the following in the CL:
```
npm run update
```

⭐️Looking for more information on Contentful UI Extensions? Check out the documentation [here](https://www.contentful.com/developers/docs/references/content-management-api/#/reference/ui-extensions).

## Reporting an issue or submitting a bug
Issues and/or bugs can be reported on this Github repository. To create a new issue, simply click the green "New Issue" button, and add a description of the issue or bug, with a method for replication if possible.
If you want to contribute to this extension, feel free to fork this repository and create a pull request, which will be reviewed by one of our team members.

## License
This extension uses an MIT license. For details, see LICENSE.md in this repository.
