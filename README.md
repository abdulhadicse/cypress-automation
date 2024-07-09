# Cypress Setup and Usage Guide

## setup
`npm init -y`
`npm install cypress --save-dev`

## open cypress application
`npx cypress open`

## headless run on background process
`npx cypress run`

## run process directly launch browser
`npx cypress run --headed`

## run process directly specific file
`npx cypress run --spec [file relative path]`

## run process directly specific a browser
`npx cypress run --browser chrome`