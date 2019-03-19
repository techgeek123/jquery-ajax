## Release 0 : Extending the Lady Gaga app from CoreBlocks/02

- Start with the webpage from the Gaga RSS exercise.
- Figure out the URL that will load in the latest tweets from LadyGaga (hint: `https://dev.twitter.com/docs/api/1/get/statuses/user_timeline`). Test in the browser to see what the JSON looks like.
- Use either raw JS or a library to load the JSON into the page.
- Create a `<ul>` with an `<li>` for each tweet. The `<li>` should contain the text and the time, where the time is linked to the individual tweet on twitter.com
- Use moment.js to pretty-print the date posted ("3 hours ago"). 
- Bonus:  Combine the news and tweets into the same `<ul>`, sorted by time.