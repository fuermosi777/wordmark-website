---
layout: page
title: FAQ
permalink: /faq/
---

## How to reset WordMark?

If WordMark is not working properly, you might need to reset the WordMark by following these steps:

### 1. Force quit WordMark

### 2. Find the user data file based on your OS

- Windows: enter `%APPDATA%` in your explorer, find and remove "WordMark" folder
- Linux: enter `~/.config` directory, find and remove "WordMark" folder
- macOS:
    - Purchased from the Mac App Store: open Finder and press `Command+shift+G`, enter `~/Library/Containers/im.liuhao.wordmark/Data/Library/Application Support`, find and remove "WordMark" folder
    - Downloaded from other sources: open Finder and press `Command+shift+G`, enter `~/Library/Application Support`, find and remove "WordMark" folder

### 3. Restart WordMark

Notice: you will lose all unsaved posts, save them before resetting.

## How to setup font?

Open "Configuration" and select "Appearence". In "Editor font" section, you can either enter the font you like or select a font from drop-down list.

## How to setup Email?

Use Gmail as an example:

```
SMTP server: smtp.gmail.com
Email: example@gmail.co
Name: <Give it a name>
Password: <password>
```

> Even though Gmail is the fastest way to get started with sending emails, it is by no means a preferable solution unless you are using OAuth2 authentication. Gmail expects the user to be an actual user not a robot so it runs a lot of heuristics for every login attempt and blocks anything that looks suspicious to defend the user from account hijacking attempts. For example you might run into trouble if your server is in another geographical location – everything works in your dev machine but messages are blocked in production. [Read more](http://nodemailer.com/using-gmail/)

## How to use relative image path in Preview?

Open "Configurations" and in "General" tab check "on" in "Enable relative path". Note that the relative path will only work when the markdown file has been saved somewhere in the operating system because otherwise WordMark does not know whom the image is relative to.

Also, even though you can see the images in Preview locally, however, it might not show correctly when you publish the post in most circumstances.