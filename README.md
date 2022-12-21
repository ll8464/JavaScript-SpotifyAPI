# JavaScript-SpotifyAPI

This is a sample project showing how to call Spotify's API using vanilla JS

## Notes

fetch API

The fetch() method is used to make HTTPS response and requests (PUT, POST, GET, DELETE).

The only mandoratory part is the URL to get the response. Fetch operates via use of Promises.

The fetch() is an async function, which allows the application to be functional while it waits for a response.

Promies are objects that are placeholders while the app waits for a response frome the server/source.

You can chain promises together via use of .then() method. It is important to always return when chaining (except the last one),
otherwise the next then() promise won't get any information.
