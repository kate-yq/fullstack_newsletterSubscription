# This is a page where you could sign up for your email posts

## How to run:
1. Download all files

2. In app.js on line 36, replace the API key with your own one.
    For safety reason, my API key is removed
    To generate a free API key, please go to mailchimp.com
    (or ignore this step and check for the fail page later)

3. $ node app.js
    to run website on local port 3000
4. open browser and type in: localhost:3000
    to access the webpage

## Funtions:
1. fill in random information and click "sign up"
2. If there is a valid API key, it will redirect to a "successful page"
3. If there is no valid API key, it will redirect to a "fail page"
    and a button that could redirect to the home page