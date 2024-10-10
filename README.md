# NotionMD

## Table of Contents
- [Features](#features)
- [Installation](#installation)

## Features
### Done features
  - Code
  - Text
  - Titles
  - Code within Text

### Peding features
  - Images
  - Bullet list
  - Numered list
  - Toggle List
  - Quotes
  - Callout
  - Divider
  - Table

## Installation

You need to export your notion integration key as 'NOTION_KEY'
Usually for unix users to add the env use the following example:

- `export NOTION_KEY=<Replace with your notion key integration>` 

Follow the steps:

-  `git clone <this repo>`
-  `cd notionmd`
-  `go mod tidy`
-  `go run main.go -db=<your db id to extract pages> -folder=<folder path where you want your pages converted if not provided create pages in current dir>`

And you're done
