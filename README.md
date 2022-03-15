# Simple Tech Blog


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Simple Tech Blog](#simple-tech-blog)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
- [Used Tech](#used-tech)
  - [Deployment](#deployment)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)

## Description

This is an MVC designed Tech blog. It allows users to sing up and write posts, add comments to other posts, and remove posts. All data is saved using MYSQL databases and sequelize to help manage routes. 

# Used Tech

- NodeJS
- Express
- Express-Sessions
- Sequelize
- bcrypt

## Deployment

[ https://murmuring-beach-17417.herokuapp.com/]( https://murmuring-beach-17417.herokuapp.com/ )

## Installation

To set up the tech blog, clone this repo, run `npm install` to get all the node packages needed.

Setup a `.env` file, with your MYSQL username, password, and database.

Run `npm start`, and your website should be up running.

## Usage

Once on the site, you must login to make a post. Click on login, and enter your information if you already have it. If not, click on signup in the lower corner, then enter the username and password you want. 

Once signed in, you can go to the dashboard, and create a new post by entering in the title and body information. 

If you want to comment on another blog post, click on the blog, and while logged in, enter your comment in the text box below.
## License

This project is licensed under a [MIT license](https://opensource.org/licenses/MIT).