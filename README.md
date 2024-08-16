# Lab Guide Snippets

## Introduction

These snippets are designed to assist in making lab guides consistently and quickly.

## How to Use

### Add Snippets

To add the snippets for Markdown in VS Code, follow these steps:

1. Open the Command Palette by pressing Cmd + Shift + P (Mac) or Ctrl + Shift + P (Windows/Linux).
1. Type "Snippets: Configure Snippets" and select the option from the dropdown list.
1. Select **Markdown** from the list of file types.
1. In the markdown.json file that opens, add the code from [markdown.json](/markdown.json), inside the existing curly braces.

    `markdown.json`

    ```json
    {
        <snippets.json goes here>
    }
    ```

1. Save and close the file.

### Use a Snippet

1. Press Ctrl + Space and select or start typing the name of the snippet.

## Available Snippets

* Create a Template: `template: Blank`
* Create a Step: `step: <optional type of step>`
* Create an Objective: `objective`
* Create a Note: `note`
* Create a Tip: `tip`

## Contributing

If you want to make improvements, please create a pull request and add your contribution.
