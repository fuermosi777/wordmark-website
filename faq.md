---
layout: page
title: FAQ
permalink: /faq/
---

* TOC
{:toc}

## How to use License Key?

A license key can be used in unlimited number of devices for unlimited length of time. Enjoy!

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

![Untitled Image](https://raw.githubusercontent.com/fuermosi777/wordmark-website/gh-pages/images/Users/hao/Library/Application%20Support/WordMark/tempClipboardImage.png)

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

![Untitled Image](https://raw.githubusercontent.com/fuermosi777/wordmark-website/gh-pages/images/Users/hao/Desktop/relative-path.png)

Also, even though you can see the images in Preview locally, however, it might not show correctly when you publish the post in most circumstances.

## How to use shortcuts?

WordMark supports following shortcuts (more are coming).

**Application**

- New markdown file: 
	- macOS: Command + N
    - Windows & Linux: Ctrl + N
- Open Configuration:
	- macOS: Command + ,
    - Windows & Linux: Ctrl + ,
- Open file or folder:
	- macOS: Command + O
    - Windows & Linux: Ctrl + O
- Publish:
	- macOS: Command + P
    - Windows & Linux: Ctrl + P
- Save current file:
	- macOS: Command + S
    - Windows & Linux: Ctrl + S
- Close current file:
	- macOS: Command + W
    - Windows & Linux: Ctrl + W
- Import HTML:
	- macOS: Command + Shift + I
    - Windows & Linux: Ctrl + Shift + I
- Toggle full-screen (macOS only):
	- macOS: Control + Command + F
- Show Editor only:
	- macOS: Command + 1
    - Windows & Linux: Ctrl + 1
- Show Sidebar:
	- macOS: Command + 2
    - Windows & Linux: Ctrl + 2
- Show Preview:
	- macOS: Command + 3
    - Windows & Linux: Ctrl + 3
- Zoom in/out:
	- macOS: Command + =/-
    - Windows & Linux: Ctrl + =/-

**Editing**

- Make current line or selected text bold:
	- macOS: Command + B
    - Windows & Linux: Ctrl + B
- Make current line or selected text italic:
	- macOS: Command + I
    - Windows & Linux: Ctrl + I
- Undo:
	- macOS: Command + Z
    - Windows & Linux: Ctrl + Z
- Redo:
	- macOS: Command + Shift + Z or Command + Y
    - Windows & Linux: Ctrl + Shift + Z or Ctrl + Y

## Why all my opened files and folders are lost after reboot?

If you downloaded WordMark from the Mac App Store, you will encounter this problem. The reason is that Mac App Store's sandbox system disallow WordMark to open file or folder without user's permission. The issue is expected to be solved in the future updates. Until then, however, you can use non-MAS version WordMark. Download it from the homepage. If you already bought WordMark from the Mac App Store, feel free to send an Email to [Customer service](mailto:hi@wordmarkapp.com) to request a free license key.