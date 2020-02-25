# Project 2

Web Programming with Python using Flask, Javascript ES6 and AJAX to make interactive web, socketIO for real time communication

# application.py
- index(): render main page - single page web
- verify(): sending request by AJAX to verify valid username created
- addDisplayName(): accept username and store into server side data-structure
- loadChannels(): load channels stored on server-side and render them on client-side
- loadMessages(): load messages of a channel and render them
- createChannel(): a user create a channel and other users are able to see it immediately thanks to socketIO
- addMessage(): a user send a message then everyone in that channel can see new message thanks to socketIO again
