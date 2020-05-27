# Snip ✂️

**Snip** is a proof-of-concept web app in which you can enter a list of things and mark them using a check box. It's kind of like a To-Do list, but more generic.

Every list is called a *snip* (short for snippet).

## How does it work?

It's literally just a web page. It doesn't even need to be served via a web server. It keeps its own state in the URL, encoded in base64. Every time you add, change or delete an entry, it will update the URL to reflect the new state.

## Usage

1. Simply enter your items one by one. When pressing enter you can immediately add a new item. 
2. Once you're done, you san save your list by simply bookmarking it in your web browser.
3. Retrieve the list at any time by accessing the bookmark. Since it's just a URL, it's also easily shareable.
