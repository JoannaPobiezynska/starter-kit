# starter-kit
Quick start for a new website. Live server, sass compilation,

## Installation
1. clone or download the project
```
git clone https://github.com/JoannaPobiezynska/starter-kit
```
2. install all dependencies
```
npm install
```
## Usage
1. run the live server and css compiler
```
npm run start
```
2. if you are not using icon fonts in your project remove fonts folder and icon-font.css file from css folder

## Build
1. build your project with npm run build. if you are not using icon-fonts please make sure to remove css/icon-font.css from concat:css script
```
npm run build
```
2. remove link to icon-font stylesheet from the head of your index file. this file is already added to your minimized css
```
 <link rel="stylesheet" href="css/icon-font.css">
 ```

## History
version 1.0
