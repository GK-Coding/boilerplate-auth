# Auth Boilerplate

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

A basic authentication boilerplate using the methods seen in Traversy Media's video [Node.js App From Scratch](https://www.youtube.com/watch?v=SBvmnHTQIPY). You should definitely watch the video first to understand how everything works, but I wanted a quick way to set up an authentication layer, to avoid the tedious setup at the start of each new project.

## Getting Started <a name = "getting_started"></a>

After pulling the code, you will need to run an npm install, and then rename the config.test.env file to config.env and change the GOOGLE_CLIENT_ID and GOOGLE_CLIENT_SECRET to your id and secret. If you don't have those, you must get them from Google. The process of doing that is explained in the video above around the 34 minute mark.

You will also need to create a new cluster in MongoDB, and then change the MONGO_URI field to you SRV connection string. Upon doing this, the system should run.

## Usage <a name = "usage"></a>

Once you have the code working, the next thing is to start adding your project's code and rename things.

Below is a list of files and the strings that should be find-and-replaced
```
package.json: 'boilerplate-auth'
package-lock.json: 'boilerplate-auth'
views/partials/_header.hbs: 'Boilerplate'
views/layouts/main.hbs: 'Boilerplate'
views/layouts/login.hbs: 'Boilerplate Login'
views/login.hbs: 'Boilerplate', 'Sign Up for whatever idea I came up with this time!'
```
