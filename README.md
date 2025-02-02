# Maulany Citra's personal blog documentation.

Welcome to the documentation for my personal blog, powered by Hugo and hosted on GitHub Pages! Here you will find a detailed guide that explains how I set up, configured, and deployed my blog. This documentation is also a part of my learning process and a showcase of my technical skills in web development.

## Project Overview
This is a personal blog created using the Hugo static site generator. It serves as a platform for sharing articles, tutorials, and personal insights. The blog is deployed on GitHub Pages, allowing anyone to view the content online.

## 1. Hugo Installation
Step: Download and install Hugo according to the operating system you're using.
Documentation: To get started with Hugo, download the latest release from the Hugo Releases page. Follow the instructions for your specific operating system.

## 2. Choosing a Template & Creating a New Project
Step: Choose a template from the Hugo Themes gallery and create a new Hugo site.
Documentation: Run the following command to create a new Hugo project:
Select a theme and configure it as per your preference.

## 3. Project Configuration
Step: Configure the config.toml file to adjust the blog title, description, and other settings.
Documentation: Edit the config.toml (or config.yaml) to set your baseURL, title, and description according to your needs. 
baseURL = "https://yourusername.github.io/my-blog/"
title = "My Personal Blog"

## 4. Content Development
Step: Create at least 3 blog posts with relevant content (article, tutorial, or personal notes).

## 5. Version Control with Git
Step: Initialize Git, create a new repository on GitHub, and push changes regularly.
Documentation: Follow these steps to push your project to GitHub:

`git init`
`git add .`
`git commit -m "Initial commit"`
`git branch -M main`
`git remote add origin https://github.com/yourusername/my-blog.git`
`git push -u origin main`

## 6. Deployment to GitHub Pages
Step: Build the project and deploy it to GitHub Pages.
Documentation: Run the following commands to build the site and deploy to GitHub Pages:

`git checkout --orphan gh-pages`
`git add public -f`
`git commit -m "Deploy to GitHub Pages"`
`git push origin gh-pages --force`

## 7. README Documentation
Step: Create a README.md file to explain all the steps of installation, configuration, and deployment.
Documentation: This document serves as the guide for setting up and deploying the blog.