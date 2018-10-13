---
title: Deploy React to Github Pages
image: "/assets/img/ghpages"
categories: javascript
---

Github pages is a greate place to host your blog and static websites which is
why I was intrigued about hosting my personal React projects there as well
instead of Firebase.  It surpised me how simple it is so lets do it.

## Prerequisite

Before anything we have to create an empty repository no license, no readme
on Github.

## Step 1: Create our App

For this I used `create-react-app`.

```bash
create-react-app my-project
cd my-project
```

## Step 2: Setup git

Now we have to configure git for our project. We have to initialize git in
our project and add our github repository:

```bash
git init
git remote add origin https://your-link.git
```

## Step 3: Setup package.json

We have to add the link our project will live at in our `package.json` at the top.
The location is simple:

```json
"homepage": "https://your-username.github.io/your-repo-name"
```

## Step 5: Install gh-pages

This package is responsible for putting the content of our `build` folder into
its own branch `gh-pages`  on our github repository. We add it to our dev
dependencies:

```bash
yarn add -D gh-pages
```

## Step 6: Add deploy script

`create-react-app` generates a `package.json` which has several predefined
scripts to run the developement server, build our project, run our tests, etc.
We are going to add a simple script that does the job for us so that we just
have to run it each time we want to deploy our app. Normaly we would have to
build our project first and then run the gh-pages command to deploy our project:

1. yarn build
2. gh-pages -d build

But we are lazy so we add this line to our scripts:

```json
"deploy": "yarn build && gh-pages -d build",
```

Each time we want to deploy our project we just run that script:

```bash
yarn deploy
```
