# Disguise-o-Rama Coding Challenge!

Your mission, should you choose to accept it, is to help Scotch Mornington (the French Girls mascot) escape being wrongfully convicted of...something...by building an app to dress him up in other costumes.  If you think you're up to the challenge, read on...

## Let's get acquainted...

Let's get you up to speed with what exactly you're building.  First watch the video [here](https://github.com/FrenchGirls/ios-coding-challenge/blob/master/demo_video/Disguise-o-Rama%20Demo.mov) to see a walkthrough of the app.

You should note the app basically has two components:  The intro screen which explains how the app works to the user, and the main screen that lets the user select a costume for Scotch.  Most of the action happens on the second screen, so let's talk about that.

The thumbnails for Scotch's costume float behind scotch, and have quite a bit of control.  You should be able recreate these controls to drag the thumbnails, fling them, select them, deselect them, and whatever other fun you want to have with them!  When a thumbnail is selected, it should zoom onto Scotch, and all other thumbnails should fall away.  Once they're selected, they should all move back into their original position.

You'll also note that when you first arrive at the main screen, there are three costumes to choose from (one is hiding behind Scotch's legs), but after a minute, 2 more pop in.  The initial three costumes should be shipped with the app as defaults, and you'll need to download the others.  In order to make this an awesome experience for your users, you'll want to keep the newly downloaded images so that they don't need re-downloaded next time!

## What you'll need

First, check the res folder of this project.  We've included all the great assets that our artist Graydon has made for us!  They include:
* config.plist
    * The configuration information for the default costumes in plist form.  The API will mirror this structure.  Be sure to check the alignment information.  Hint:  display_x/y helps align the thumbnails, and alignment_x/y helps align the costumes on top of Scotch.
* Assets.xcassets
    * The asset catalog you'll need for everything in the app.  This includes the icons, the splash screen images, a speech bubble image, Scotch and his costumes.
* fonts.txt
    * A description of all fonts, sizes and colors

The only other resource you should need is our REST API set up for this project.  There's only a single endpoint at: http://ivdemo.frenchgirlsapp.com/api/current_costumes.json

## What we expect from you

We understand that you don't have all the time in the world to set around and code hilarious apps, so we don't necesarily expect you to complete this app fully, although if you do, more kudos to you.  However, we want to see how you plan and attack an app from the ground up that includes some basic REST API usage, fancy UI, and a little architecture.  So here's what we'd like you to do:

1. Create a github repo, and commit an empty README.
1. Take some time to figure out all of the different tasks that need to be done to complete this app.  Write them down as if you were planning this project yourself.  These may take the form of user stories, checklists, an outline of features, whatever makes the most sense to you.  This step doesn't need to be very technical, it just needs to identify all the unique chunks of work that you think would be required to complete this app.  However you decide to tackle it, document your work in your github repo.
1. Next, take some time to get more technical.  Plan out what the major technical components are, and define how they work together.  This is your chance to be an architect and make high-level decisions about what technology you want to use, and how you want to implement it.  Write this technical strategy down in a way that you feel would be useful if you were to actually code this project.
1. Commit these two items to your github repo.
1. Email hiring+ios@frenchgirlsapp.com with a link to your github repo!  If you've been contacted by someone at the French Girls team, feel free to email them directly #as well#!

That's it!  Good luck, and have fun!  Hopefully we'll work with you soon!
