# PebbleGPT API Key Configuration Page

This repository hosts an HTML file `index.html` used as a configuration page for the PebbleGPT application. The main purpose of this page is to enable users to input their OpenAI API key, which is a required configuration for the PebbleGPT app to work. 

## Getting Started

### Prerequisites

Before you can use this configuration page, make sure you have the following:

1. An API key from OpenAI. You can obtain this by going to the [OpenAI API key page](https://platform.openai.com/account/api-keys).

2. A subscription to Rebble for voice transcription to work.

### Using the Configuration Page

To use the configuration page:

1. Open the hosted `index.html` file.

2. In the "API Key" input field, paste your OpenAI API key.

3. Click the "Save" button.

This will save your API key to the local storage, and it will be used by the PebbleGPT app. 

## Under the Hood

The 'Save' button is attached to a JavaScript event listener that executes a function when clicked. This function fetches the value from the 'API Key' input field and saves it to the local storage. It then navigates to a specific URL schema (`pebblejs://`) that is handled by the Pebble app, passing the API key data along with it.

## PebbleGPT App Repository

The code for the PebbleGPT app, which this configuration page is designed for, can be found at the following GitHub repository: [PebbleGPT](https://github.com/huntboom/PebbleGPT)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. (Assuming the project is licensed under the MIT License)

## Contributing

If you would like to contribute to this project, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. (If there is a contribution guideline)
