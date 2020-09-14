# SENTI

## Overview

An asynchronous web app that runs SENTIment analysis on your articles using Natural Language Processing via the AYLIEN API.

## About AYLIEN

The [AYLIEN](https://docs.aylien.com/textapi/endpoints/#sentiment-analysis) Text Analysis API is a package of Natural Language Processing and Machine Learning-powered APIs for analyzing and extracting various kinds of information from textual content. 

## How the app works

Allows users to run Natural Language Processing (NLP) on articles or blogs by simpling entering the URL. The Sentiment Analysis API will analyse the text and return pertinent information about the article, like whether the content is subjective (opinion-based) or objective (fact-based) and whether it is positive, neutral, or negative in tone. 

## Express and Webpack

Node and express will be the webserver and routing of choice, and webpack is used as the build tool. Using webpack, you have the option of building both development and production environments, each with their own set of tools and commands with package.json scripts.

## Tech stack

- HTML
- SASS
- Javascript
- Server: Node.js
- Router: Express
- Build Tool: Webpack Loaders and Plugins
- External Script: Service workers
- External API: AYLIEN
- Testing: JEST

## Installation instructions

- Clone project repository:

  `$ git clone https://github.com/Enid-Sky/evaluate-the-news-nlp.git`

- Install all development dependencies and dependencies of the package.json:

  `npm install`

- Get an API Key and ID from [Aylien](https://docs.aylien.com/textapi/#getting-started) and save it to the file called .env:

  `API Key = <You Key>`
  `API ID = <Your ID>`

## Run in development mode

`npm run build-dev`

## Run in production mode

`npm run build-prod`
`npm run start`

## Run JEST tests

`npm jest-test`

## Stop application

`CTRL + C`
  
*****

# Demo
![image](https://user-images.githubusercontent.com/43654264/93033809-afdffb00-f5ec-11ea-9e1a-0340e3c3c074.png)

*****
## Negative Tone
![image](https://user-images.githubusercontent.com/43654264/93034014-7eb3fa80-f5ed-11ea-9b19-c5407f63ae3c.png)

*****
## Neutral Tone
![image](https://user-images.githubusercontent.com/43654264/93034141-ecf8bd00-f5ed-11ea-81c2-002089c362ee.png)

*****
## Neutral Tone
![image](https://user-images.githubusercontent.com/43654264/93034275-68f30500-f5ee-11ea-80c3-dd851285a6ca.png)



