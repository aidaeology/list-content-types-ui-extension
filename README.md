# list-content-types-ui-extension
A custom UI extension for use with Contentful that displays a list of content types in the current space.
Please visit https://www.contentful.com/r/knowledgebase/ui-extensions-guide/ to learn how to install in Contentful Web App.

# Usage
This UI extension is designed to be used with [Contentful](http://www.contentful.com), you will need a space ID as well as a CMA access token. The UI extension retrieves a list of content types based on some criteria (default example uses sys.id name match) URL and populats a dropdown list in the UI. When the user makes a selection from dropdown, it sets the value on the field.

1. Install this UI Extension in your Contentful space.
2. Update the SPACE_ID and CMA_TOKEN in the extension source (html). Don't forget to save!
3. Update the filter in getSecureContentTypes function to match your requirements.
2. Create a field on your content type and set its type to Symbol.

# Notes
This UI extension is intended for demo & inspirational purposes only and not tested or supported by Contentful for production use.
