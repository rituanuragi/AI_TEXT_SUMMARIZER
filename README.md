# AI_TEXT_SUMMARIZER

This is a web application built using React.js that utilizes the OpenAI API through RapidAPI to summarize large blocks of text into shorter, more manageable chunks. It also allows users to save the history of their previous requests and includes a copy button to easily copy the summary to the clipboard.

**#Technologies Used**

1.React.js

2.OpenAI API through RapidAPI

3.Vite

4.Tailwind CSS

5.Redux Toolkit

**#Requirements**

1.Node.js v14.x or higher
2.npm

**#Installation**

Install the required packages:

npm install

Create a RapidAPI account and subscribe to the OpenAI API.

Create a .env file in the root of the project and add your RapidAPI key:
REACT_APP_RAPIDAPI_KEY = YOUR_API_KEY_HERE

Start the development server:
npm run dev

**#Usage**

To use the AI-Text-Summariser, open a web browser and navigate to http://localhost:3000. Enter the URL of the article or text you wish to summarize and click the "Summarize" button. The summary will be displayed on the page, along with the option to copy it to the clipboard. The application will also save a record of the previous requests in the history section.

The website can also be viewed on Netlify at [https://articlesummariser.netlify.app.](https://app.netlify.com/sites/exquisite-kitsune-db51b1/overview)

**#Customization**

The application can be customized by adjusting various parameters in the src/config.js file, such as the maximum length of the summary and the maximum number of previous requests to display in the history section.

**#Acknowledgements**

This project was inspired by the need for a simple and efficient way to summarize large blocks of text and was developed using the OpenAI API through RapidAPI.
