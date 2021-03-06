# Offline news website

We’re going to make a simple offline-first to-do application with HTML5 technology. Here is what the app will do:

- store data offline and load without an Internet connection;
- automatically download the latest stories when there is a good connection;
- run on the first- and second-most recent versions of all major desktop and mobile browsers;
- list the latest news headlines as well as allow users to click into an article;
- **have a unique URL for each of the articles, and the list of articles page.**

The last point is highlighted because it's the key distinguishing feature that makes making a website work offline different, and substantially harder, (with AppCache) than "single page apps" like the one described in the previous section.

## Why news?

Content-based websites (which includes websites other than news sites, such as Wikipedia, where the focus is on **reading** rather than **doing** make up a huge proportion of the world wide web)
but are a use case that stretches AppCache to its limits.

This makes building a simple offline news website a good example to explore AppCache and its replacement, Service Worker, in depth.  Also it will be possible to takes these tips and tricks and apply them **immediately** to most websites.

---

[← Back to *success*](../04-offline-todo-with-sync/05-success) | [Continue to *scaffolding* →](01-scaffolding)
