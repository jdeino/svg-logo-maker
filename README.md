# svg-logo-maker

## Description
I have created a command line application that generates custom logos and saves as SVG files. User is prompted with a few questions to help create logo such as text, text color, shape, and color of shape. Once questions are filled out the "inquirer" package generates it as an SVG logo file.

- Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Demo](#demo)

## Installation
Run the following to install dependencies. 
```
npm install
```

## Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I am prompted for text
THEN I can enter up to three characters
WHEN I am prompted for the text color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I am prompted for a shape
THEN I am presented with a list of shapes to choose from: circle, triangle, and square
WHEN I am prompted for the shape's color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I have entered input for all the prompts
THEN an SVG file is created named `logo.svg`
AND the output text "Generated logo.svg" is printed in the command line
WHEN I open the `logo.svg` file in a browser
THEN I am shown a 300x200 pixel image that matches the criteria I entered

## Demo
[Demo]https://drive.google.com/file/d/16tcUJsNGJO96Eb_Rrmy1ZzU_lqFYm4d0/view
