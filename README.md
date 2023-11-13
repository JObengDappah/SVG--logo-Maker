# SVG--logo-Maker

## Table of Contents

-[Description](#description)
  -[Installation](#installation)
  -[Usage](#usage)
  -[License](#license)
  -[Acceptance-Criteria](#acceptance criteria)

## Description

This is a Node.js-based command-line tool that enables users to create a logo by inputting their preferences. The application guides the user to choose a color and shape, and to input text for the logo. Once the design is complete, it saves the resulting logo as an SVG file.

## Installation

Install the packages by running npm init then run npm i inquirer and jest

## Usage

  [Video Demo](https://drive.google.com/file/d/1C5wfGDBX6Ivhc81cFfPIVdN0dyP06l-o/view?usp=drive_link)

## License

  [![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
    ### licensing
    This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.
    [![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Questions

  For questions or concerns, you can reach out to <jacmo074@gmail.com>.
  Github: [JObengDappah](https://github.com/JObengDappah)

### Acceptance Criteria

* GIVEN a command-line application that accepts user input

* WHEN I am prompted for text

* THEN I can enter up to three characters

* WHEN I am prompted for the text color

* THEN I can enter a color keyword (OR a hexadecimal number)

* WHEN I am prompted for a shape

* THEN I am presented with a list of shapes to choose from: circle, triangle, and square

* WHEN I am prompted for the shape's color

* THEN I can enter a color keyword (OR a hexadecimal number)

* WHEN I have entered input for all the prompts

* THEN an SVG file is created named `logo.svg`

* AND the output text "Generated logo.svg" is printed in the command line

* WHEN I open the `logo.svg` file in a browser

* THEN I am shown a 300x200 pixel image that matches the criteria I entered
