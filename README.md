# Slack Command Example Project

This is an example project that implements a basic slack command handler. It handles a slack command in the form "/[command] [page url] [subject]" and does the following:

* Scrapes the images from the specified page
* Filters the images to match the desired subject using AWS Rekognition
* Posts the matching images back to Slack
