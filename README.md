# TempoGPT
A simple bot template using the openAI API key to do a specific task through function calling &amp; tools. In this case, a weather type bot example using the OpenWeather API. Additionally using firebase to store messages. Made in ReactJS.

## Deployment

1. Usage

```
  git clone https://github.com/vahshellus/TempoGPT.git
```
or simply download the .zip.


2. Install
Use `npm install` to install all of the required dependencies.

3. Deploy
- Use `npm run dev` to deploy the application.
- Navigate to /src/backend and deploy server.js through `node server.js` (This is where the route will be used to transfer requests.)

## Replacements
- Replace the data in firebase.js with your own firebase web app configurations.
- Add in your openAI API key in `chatbot.py` at `OpenAI(api_key='')`
- If you wish to use the weather api in the example, sign up for the OpenWeatherMap for free and add in your API key in `API_KEY`. 

## Possible Python Error
- In `server.js` I'm using `spawn('python3', ['../utility/chatbot.py']);` , if you're using another version of python or  "plain" `python` , then just replace `python3` by `python`

## Demo
![image](https://github.com/vahshellus/TempoGPT/assets/60050784/cfcb4a6a-a0df-4a82-953f-2c9caf17f035)
