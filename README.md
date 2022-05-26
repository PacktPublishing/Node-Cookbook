## [Get this title for $10 on Packt's Spring Sale](https://www.packt.com/B05269?utm_source=github&utm_medium=packt-github-repo&utm_campaign=spring_10_dollar_2022)
-----
For a limited period, all eBooks and Videos are only $10. All the practical content you need \- by developers, for developers

# Node Cookbook - Third Edition
This is the code repository for [Node Cookbook - Third Edition](https://www.packtpub.com/web-development/node-cookbook-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785880087), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
The principles of asynchronous event-driven programming are perfect for today's web, where efficient real-time applications and scalability are at the forefront. Server-side JavaScript has been here since the 90's but Node got it right.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
const express = require('express')
const app = express()
const past = require('./past')
const future = require('./future')
app.get('/:age', (req, res) => {
    res.send(past(req.params.age, 10) + future(req.params.future, 10))
})
app.listen(3000)
```

The following is a list of the software that is required to run the examples in this book:
* Chapters 1-10: Windows, macOS, or Linux.
* Chapter 11: Linux or macOS (we recommend that Windows users work through Chapter 11, Deploying Node.js, by SSH-ing into a remote Linux machine).
* Node 6 or higher. In cases where the code is specific to Node 8, this is specified.
* Node can be downloaded from http://nodejs.org.
* Curl 7: Curl can be downloaded from http://curl.haxx.se.

## Related Products
* [Universal JavaScript with React, Node, and Redux [Video]](https://www.packtpub.com/web-development/universal-javascript-react-node-and-redux-video?utm_source=github&utm_medium=repository&utm_campaign=9781787286795)

* [Cross-platform Desktop Application Development: Electron, Node, NW.js, and React](https://www.packtpub.com/web-development/cross-platform-desktop-application-development-electron-node-nwjs-and-react?utm_source=github&utm_medium=repository&utm_campaign=9781788295697)

* [Building Bots with Node.js](https://www.packtpub.com/application-development/building-bots-nodejs?utm_source=github&utm_medium=repository&utm_campaign=9781786465450)
