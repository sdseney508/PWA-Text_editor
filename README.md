# PWA-Text_editor
An online text editor that can be installed and run offline using a service worker.  Powered by Node and Express.
![image](https://user-images.githubusercontent.com/62141103/168429964-08c223a9-72f8-4017-87fd-68a8640eee75.png)


## Table of Contents
 -[Installation](#installation)

 -[Usage](#usage)

 -[Credits](#credits)

 -[License](#license)

 -[Badges](#badges)

 -[Features](#features)

 -[How To Contribute](#contributing)

 -[Tests](#tests)

 -[Questions](#questions)


 ## Installation
 💾The app is fully deployed at:
https://steves-text-editor.herokuapp.com/

It can be run purely online or installed and run offline by clikcing the install button at the top left hand corner of the screen.  Once installled, it will update the online database on every reconnection.

For a local install and run, install all of the files and folders then run:    
```
npm i
npm run build
npm run start
```    
Then launch a browser and open it to 'localhost:3000'

 ## Usage
 None
 ## Credits
 None
 ## License
 ![badge](https://img.shields.io/badge/license-MIT-blue)

License file can be found at:  

https://github.com/sdseney508/PAW-Text_editor/blob/main/license.txt

 ## Badges
N/A
 ## Features

# Acceptance Criteria

## USer Stories
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application

WHEN I open my application in my editor
THEN I should see a client server folder structure

WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client

WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack

WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file

WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors

WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage

WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB

WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB

WHEN I click on the Install button
THEN I download my web application as an icon on my desktop

WHEN I load my web application
THEN I should have a registered service worker using workbox

WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
 ```

 ## Contributing 
 N/A
 ## Tests
Manual tests using Insomnia were run for all routes to the server.  

 ## Questions
For questions on usage or functionality i can be reached at:

Github: [sdseney508](https://github.com/sdseney508)

E-mail: sdseney508@gmail.com
