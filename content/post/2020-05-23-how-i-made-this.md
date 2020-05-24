---
title: "2020 05 23 How I Made This"
date: 2020-05-23T17:14:16-04:00
draft: true
---

In the interest of sharing, I thought it might be valuable if I published an article explaining exactly how I put this site together.

Here's an outline of the resources you'll need to build something similar.

1. CMS
2. Hosting
3. Souce Code Control
4. CI/CD

## CMS: HUGO

I spent years building, customizing and writing plugins for [Wordpress](https://wordpress.org) but over the years I stopped writing PHP code and leaned heavily into JavaScript. This led me away from Wordpress and into the world of JAMStack. I began writing applications using Node.JS and hosting some of them in Netlify. Once I began getting familiar with Netlify, someone introduced me to Hugo - Hugo and Netlify go great together. I deployed the original MongoDB.dev site using that and fell in love with the ease of use. So when it came time to deploy a web site for Zero to Live, I chose Hugo. I'll talk more about where and how I'm hosting the project coming up.

## Hosting: MongoDB Realm

As I mentioned, Hugo and Netlify go great together so that would have been a no-brainer. However, I happen to work for [MongoDB](https://www.mongodb.com) and they've got a hosting solution that I've used for many projects. It's not well known but MongoDB Realm has a static content hosting capability built right in. 