# Rubeun's Bookmark & URL shortening Server

An example of a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

View demo at: [https://rubeuns-bookmarks.herokuapp.com/](https://rubeuns-bookmarks.herokuapp.com/)

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

