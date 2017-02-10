# BibleJS
## What does it do?
This program reads a verse from the KJV bible using an internet connection.

## Requirements
It needs NodeJS to be installed on you computer. Here is the [site](https://nodejs.org).

## Usage
This is a command-line program so you need to open a command shell or command prompt, cd to the folder of verse.js and then execute:  
`node verse.js [argument]`  

(On the first usage only, you should do a `npm install`, before usage, when inside the folder of verse.js, to install the verse.js dependencies).  

The argument can be a bible reference (such as Genesis 6:3) or the number of the verse (from 1 to 31102).  
So the program can be run with these options, from example:  
`node verse.js "Genesis 2:1"`  
`node verse.js 131`
