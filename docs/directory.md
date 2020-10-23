---
layout: default
title: Directory Structure
nav_order: 2
---

# Directory Structure
{: .no_toc }

1. TOC
{:toc}

Yahmi application have following directory structure

1. app
2. config
3. public
4. resources
5. storage
6. test
7. vendor


# [](#app)app

This directory contains other sub directories as mentioned below.

 - **Controllers:** Here you can find all applicatin controllers
 - **Middlewares:** Here you can define middlewares as needed. Middleware are needed for controllers. Which we can resuse for each controller method. After adding middlewares in this directory you have to register it in app/Kernel.php inside $routeMiddlewares array.
 - **Models:** Application models resides here.

# [](#config)config

Inside config directory you will find all configuration needed for the application. Most important config files are
- **app.php:** Application specific configuration resides here.
- **database.php:** Database connection and other databasees configuration resides here.
- **paths.php:**  View template engines paths configuration.


