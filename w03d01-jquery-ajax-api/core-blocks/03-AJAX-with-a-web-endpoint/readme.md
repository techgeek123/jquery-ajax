## Release 0 : Working with Google Docs and AJAX 

In this exercise we're going to learn how we can use AJAX to interact with various web end points. We will be working with the Google Docs end point here but this could be any other service as well. (Read up on what other services can be used with AJAX)

- Create a new Google spreadsheet.
- Add columns for “item”, “quantity”, and “requestor”.
- Add 5 rows (whatever your fridge is missing!).
- Publish the spreadsheet (via File->Publish as webpage).
- Use the [JSONP technique](https://stackoverflow.com/questions/2067472/what-is-jsonp-all-about) to bring the published feed into your page as JSON.
- The URL should be of this form: `https://spreadsheets.google.com/feeds/list/o03712292828507838454.2635427448373779250/od6/public/basic?alt=json-in-script&callback=listTasks`
    - The structure of the URL is like `http://spreadsheets.google.com/feeds/list/{SPREADSHEET_KEY}/{WORKSHEET_ID}/public/basic?alt=json-in-script&callback={callbackName}`

- The spreadsheet key is usually in the URL, the worksheet ID is always od6 for the first worksheet, and callback name is whatever your function is called.

- Create a `<ul>` with each shopping item as an `<li>`.

## Release 1 : Add images
- Use the [Google Custom Search API](https://developers.google.com/custom-search/) to find an image for each item.
