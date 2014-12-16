---
layout: archive
permalink: /setup/first-time-use/
title: "First time use"
toc: true
---

## First time use

You'll need to do the following steps:

* Create an [Application on Spotify](https://developer.spotify.com/my-applications) (this is for both free and premium users)
    * You can set Application Name and Description to whatever you want
    * ***Redirect URI must be set to*** `http://localhost:15298/callback.php`
    * ***Make sure to click 'Save' button once you set the Redirect URI***

![Example](http://cl.ly/image/0h2F1z232Q2p/Capture_d%E2%80%99e%CC%81cran_2014-11-04_a%CC%80_11_13_50.png)


* Invoke the workflow and follow the steps as below by copy/pasting the Client ID and Client Secret into Alfred window when asked:

![Paste Client ID & Client Secret](http://cl.ly/image/2g0r1a2V3h1a/Screen%20Recording%202014-11-13%20at%2009.33%20AM.gif)

* Invoke the workflow again and select Authenticate with Spotify, your web browser will open and you'll be prompted to login with Spotify and allow access to your application. At the end you should see a page where it says you're successfully logged.

* Invoke the workflow again and Create the library, or update existing one as needed.

* After some time, you should get a notification saying that library has been created.

**Note that the first time the library is created, all artworks are downloaded, so it takes quite some time. But don't worry next updates are very quick!**

You can check progress by invoking the workflow again:-

![Screenshot](http://cl.ly/image/06362e2g1a09/Capture%20d%E2%80%99e%CC%81cran%202014-11-27%20a%CC%80%2016.50.44.png)