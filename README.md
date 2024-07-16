# Salesautomators_test

This repository contains a simple HTML form that allows users to submit data to Pipedrive.

## Features

* **Dynamic form creation:** The form is dynamically generated using JavaScript, allowing for easy customization of fields and sections.
* **Pipedrive integration:** The form submits data to a Pipedrive API endpoint, creating a new deal in your Pipedrive account.
* **User-friendly interface:** The form is designed with a clean and intuitive layout, making it easy for users to fill out.

## Installation

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.

## Usage

1. Fill out the form fields with the required information.
2. Click the "Create job" button to submit the form.
3. A new deal will be created in your Pipedrive account.

## Customization

You can customize the form by modifying the following:

* **Fields:** Add, remove, or modify the form fields using the `createInput`, `createSelect`, and `createTextArea` functions in the JavaScript code.
* **Sections:** Add, remove, or modify the form sections using the `createElement` function in the JavaScript code.
* **API token:** Replace the `apiToken` variable in the JavaScript code with your own Pipedrive API token.
