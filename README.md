# Instagram-Clone
Instagram Clone with both serverside and clientside dynamic pages

This project aimed to replicate the popular social media platform Instagram, allowing users to interact with each other by following them, viewing posts, and adding likes and comments.

Some functionalities of the project:
- Users must log in with their (secure) credentials or create a new account
- Once logged in, users are taken to the index page, where they can view and interact with the posts of any users that they follow.
- A link to an "explore" page is included, where users can view which users they don't follow and choose to follow them if they wish.
- A link to a "profile" page is included, where users can view their own profiles, included their posts and personal information, and edit any information (passwords, email addresses, name, etc) if they wish.

At first, the project was written with a full server-side implementation. The Python Flask library was used in concurrence with HTML templates to allow the server to receive and act on any requests sent to it.

To optimize some functions of the project, particularly those relating to POST requests (avoiding a page reload), some pages were redone with a clientside implementation. This involved the use of ReactJS and a REST API, calling JavaScript code which would allow the user to view changes to these pages without a full page reload.

Data was stored in a local SQLlite relational database, for simplicity. A larger-scale implementation would require additional measures. The only data stored related to user login information, and activity related to posts (image files, likes, comments, timestamp).

Please feel free to email me at rohanagr@umich.edu, I'd be happy to discuss this project further!
