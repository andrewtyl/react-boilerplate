# React Boilerplate
## Boilerplate
This is a boilerplate template bootstrapped and then modified with [Create React App](https://github.com/facebook/create-react-app). The modifications were made to better suit my needs compared to the standard Create React App, and hopefully they suit yours as well.

## Set Up
1. Open a terminal and `cd` to where you want the new project folder to be.
2. In terminal, run `git clone https://github.com/andrewtyl/react-boilerplate.git NEW-PROJECT-NAME ; cd NEW-PROJECT-NAME`
3. Delete `.git` folder using a file exploring program or run `rm -rf .git` in terminal. (The folder/files may be hidden from your file explorer.)
4. In terminal, run `git init ; npm i .`
5. Create a 512x512 png of what will become your icons on browsers and mobile devices.
6. Upload that image to https://favicon.io/favicon-converter/ and download the zip file. Extract the zip file and save and replace ONLY the favicon.ico file to the repo in `./public/`
7. Upload that image again, this time to https://app-manifest.firebaseapp.com/. Fill out all the information too, and then download the zip. Extract all contents of that zip file to `./public/`
8. Update `./public/index.html`. The lines in question have comments next to them.
9. Edit `LICENSE` to include your name, the year if maintaining an MIT license. Otherwise, replace the `LICENSE` file with your own license.
10. Edit `name`, `description`, and `repository` in `package.json`
11. Edit `version`, `author`, `keywords`, and `license` in `package.json` if needed.
12. Edit this file to include your app's name and description. It is reccomended to keep a backup of this file before altering it and add it to .gitignore or to reference the readme at https://github.com/andrewtyl/react-boilerplate/blob/master/README.md for additional information about Scripts and Deploying.

## Scripts
* `npm start` - starts the react server locally
* `npm test` - runs all test files
* `npm run build` - creates a build of the web app for deployment
* `npm predeploy` - creates a build of the web app for deployment and then runs a server of the build locally

## Reccomended File Organization

## Deployment

###### License
MIT License

Copyright (c) 2020 AJessen and Andrew Jessen-Tyler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR I