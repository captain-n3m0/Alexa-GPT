# Alexa-GPT
An Alexa skill that uses ChatGPT to generate responses to user input. This code is written in Node.js and uses the "ask-sdk-core" library to handle Alexa requests and responses, as well as the "axios" library to make HTTP requests to the ChatGPT API.

## Deployment

* Go to the AWS Console and navigate to the Lambda service.

* Click "Create Function" and select "Author from scratch". Enter a name for your function, select Node.js 14.x as the runtime, and choose "Create a new role with basic Lambda permissions" for the execution role.

* Click "Create function" to create the Lambda function.

* In the function code editor, replace the default code with the code from my previous response.

* Click "Save" to save the function code.

* Go to the "Configuration" tab of your Lambda function and add a new trigger. Select "Alexa Skills Kit" as the trigger type.

* Go to the "Designer" tab of your Lambda function and click "Add" in the "Environment variables" section. Add a variable named OPENAI_API_KEY and set its value to your OpenAI API key.

* Click "Save" to save the changes to your Lambda function.

* Copy the ARN of your Lambda function.

* Go to the Alexa Developer Console and create a new skill. Follow the steps in the console to configure your skill's name, invocation name, and interaction model.

* In the "Endpoint" section of your skill's configuration, select "AWS Lambda ARN" as the service endpoint type. Paste the ARN of your Lambda function into the "Default Region" field.

* Click "Save Endpoints" to save the endpoint configuration.

Your Alexa skill is now configured to use ChatGPT to generate responses to user input. Test your skill in the Alexa Developer Console or on an Alexa-enabled device.

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## License

[MIT](https://choosealicense.com/licenses/mit/)

