# leean-webapp
Starter Web App based on the modular/atomic Leean concept.

Based on the [Angular Seed](https://github.com/angular/angular-seed) project. Follow the link to check the documentation.

Point your DocumentRoot at the /www folder to run the app. Or you can use ```npm start``` as described in the Angular Seed project.

## Getting Started

### Clone the repo
To start a new project without the moxie-leean/web-app commit history you can run:

```
git clone --depth=1 git@github.com:moxie-leean/web-app.git <your-project-name>
```

The depth=1 tells git to only pull down one commit worth of historical data.

### Install Dependencies
Web App uses npm to manage dependencies. Run the following in the project's root directory:

```
npm install
```

[Download NPM / NodeJS](https://nodejs.org) first if you don't already have it installed globally.

### Create Fake API data
First you need to globally install the JSON Server if you don't already have it:

```
npm install -g json-server
```

Then design your API structure and add your fake JSON data to ```json-data.json``` (sample file included with this project for you to edit).
 
Finally run the following in the project's root folder to start the server:

```
json-server --watch json-data.json
```

Your API will be available at [http://localhost:3000/](http://localhost:3000/), e.g. [http://localhost:3000/posts/1](http://localhost:3000/posts/1)

See the [JSON Server Documentation](https://github.com/typicode/json-server) for more options.
