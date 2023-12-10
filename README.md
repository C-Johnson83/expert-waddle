# expert-waddle
Repository for module 14 challenge assignment- Model-View-Controller (MVC) Challenge: Tech Blog

# Description
Writing about tech can be just as important as making it.  
Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies.  
A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

## Objective
My goal is to build a CMS-style blog site similar to WordPress.  
Developers can publish posts and comment on others' content.  
I will be structuring the app using the MVC paradigm, implement Handlebars.js for templating, Sequelize for ORM, and use express-session for authentication.  
The final step will be deploying the site to Heroku. 

## Table of Contents
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## User Story
AS A developer who writes about tech  
I WANT a CMS-style blog site  
SO THAT I can publish articles, blog posts, and my thoughts and opinions


## Acceptance Criteria  
GIVEN a CMS-style blog site  
WHEN I visit the site for the first time  
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in  
WHEN I click on the homepage option  
THEN I am taken to the homepage  
WHEN I click on any other links in the navigation  
THEN I am prompted to either sign up or sign in  
WHEN I choose to sign up  
THEN I am prompted to create a username and password  
WHEN I click on the sign-up button  
THEN my user credentials are saved and I am logged into the site  
WHEN I revisit the site at a later time and choose to sign in  
THEN I am prompted to enter my username and password  
WHEN I am signed in to the site  
THEN I see navigation links for the homepage, the dashboard, and the option to log out  
WHEN I click on the homepage option in the navigation  
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created  
WHEN I click on an existing blog post  
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment  
WHEN I enter a comment and click on the submit button while signed in  
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created  
WHEN I click on the dashboard option in the navigation  
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post  
WHEN I click on the button to add a new blog post  
THEN I am prompted to enter both a title and contents for my blog post  
WHEN I click on the button to create a new blog post  
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post  
WHEN I click on one of my existing posts in the dashboard  
THEN I am able to delete or update my post and taken back to an updated dashboard  
WHEN I click on the logout option in the navigation  
THEN I am signed out of the site  
WHEN I am idle on the site for more than a set time  
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts


## Installation



## Usage

## Features

## Contributing

Thank you for considering contributing to the sturdy-fiesta project!  
To maintain the integrity of the codebase, please refrain from making direct changes to the repository.  
If you have suggestions, bug reports, or feature requests, feel free to reach out by contacting Chris at chrisj21293@gmail.com.  
We welcome contributions through thorough bug reports or feature requests via GitHub Issues.

If you have a specific improvement or feature you'd like to work on, please follow these guidelines:

1. **Fork the repository:** Click the "Fork" button on the top right of the repository page.
   
2. **Create a new branch:** Switch to a new branch to isolate your changes.
   ```bash
   git checkout -b feature-name
   ```

3. **Make your changes and commit them:**
   ```bash
   git commit -m 'Add new feature'
   ```

4. **Push to your created branch:**
   ```bash
   git push origin feature-name
   ```

5. **Create a pull request:** Submit a pull request from your forked repository with a detailed description of your changes.

Your cooperation is appreciated, and we look forward to hearing from you!

## License
This project is licensed under the MIT license.  
License Link  
https://opensource.org/licenses/MIT   
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]  