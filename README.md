## I have no idea what Plug.dj did, but it's a missing function in the API that's been there since day 1.  I've contacted Steven so you'll just have to wait until I get a response from him.

## Plug.bot

A collection of extensions to the growing online DJing website, <a href="http://plug.dj">plug.dj</a>.  The source code is written in JavaScript and uses the Plug.dj API anywhere possible.  Easily embeddable as a bookmark in your favorite browser.  Initially inspired by TechGuard's AutoWoot script from April 2012.

###<strong>I'm running out of ideas about what to add to Plug.bot.  If you have any ideas, e-mail me!</strong>


### Features List ###

Feature | Purpose
--------|--------
Auto Woot | Automatically WOOT! each song as it is played
Auto Queue | Automatically add yourself back to the DJ Waitlist once you've been moved back into the crowd
Userlist | A dynamic list of every user in the room, color-coded by their current vote.  Green = "Woot", Red = "Meh", White = No vote  Special usergroups (i.e. moderator) are denoted by the icon you'd normally see in the chat
Toggle UI | Allows you to easily configure your Plug.bot experience;  enable or disable each of its features at the click of a button.  Red = Off, Green = On
Hide Video | Hides videos from view on the site -- this is in effect until disabled
Skip Video | This is exactly like hide video, except it additionally mutes the audio and will automatically re-enable everything after the current video is over


### Installation ###

Drag the text from the link below (it will look like code) into your Bookmarks Bar and it should make a new bookmark.  You can label it yourself, it doesn't matter.  Then just click the bookmark whenever you're on Plug.dj and you're good to go.

Install [this bookmarklet](http://pastebin.com/raw.php?i=ywuQK2XA) in order to run Plug.bot.  If you have a problem with installing the bookmarklet, just Google it, there are plenty of solutions to be found.  DO NOT e-mail me about it.  The ONLY time the bookmark will ever not work is if Github is down, and that's pretty rare so don't be worried (it happened for less than 24 hours last year and then it was back to normal.)

#### YouTube Video Install Guides ####

<strong>English</strong> - https://www.youtube.com/watch?v=ClpQDwl5GPg

<strong>French (thanks Xbird!)</strong> - https://www.youtube.com/watch?v=Sfa6bktNQrc


### Author ###

+ <strong>Conner Davis &lt;connergdavis@gmail.com&gt;</strong> <em>a.k.a. Fugitive.</em>  

If you knew me as Logic, you can feel free to get mad at them for taking my original name.



### Copyright Notice ###

Plug.bot is licensed under the GNU General Public License, or GPL.  If you want to redistribute the source (for free, of course!) just retain the first 38 lines, which are all header comments.  So long as you abide by that rule and provide a link directly (no bit.ly, etc.) to <a href="https://github.com/connergdavis/Plugbot">https://github.com/connergdavis/Plugbot</a> wherever you have your version of the software, you are free to redistribute it (FOR FREE!!) as your heart desires!  Thanks for playing fair.



### For any question that isn't "How do I install Plug.bot" ###

connergdavis@gmail.com

Seriously.  If you e-mail me about a problem installing Plug.bot, it's getting deleted without a second thought.  If you have a legitimate inquiry about something related to the project, THAT'S something I'll read. 



### Version History ###


Version | Release Date | Changes
--------|--------------|--------
1.1 | March 21, 2013 | <ul><li>Added skip video, cappie01's idea</li><li>Cleaned up code consistency</li><li>Removed custom username FX (it was bad anyway)</li></ul>
1.0 | November 23, 2012 | <ul><li>Supports Plug.dj "Pepper", the newest version, introduces mostly rank changes</li><li>Revamped userlist code, faster and completely stable at this point</li><li>Userlist now allows you to @mention users by clicking their name, you can @mention multiple users as well</li><li>Over 1,000 users now!</li></ul>
0.5a | August 1, 2012 | <ul><li>Userlist font is smaller due to more users being in rooms, thanks Monstercat</li><li>Hide video now lasts until you disable it, rather than resetting each time a new song comes around</li><li>Moved the UI to be beside the chat for more space for buttons</li><li>Buttons are now HTML-generated instead of pictures</li><li>Custom username FX now allows you to highlight specific people with custom colors</li></ul>
0.4a | July 19, 2012 | <ul><li>Userlist has been re-styled!  It now looks much sleeker</li><li>Above the userlist is your current spot in the DJ waitlist, if you are in it.  This should make it easier to check instead of having to click the button and look for yourself</li><li>Removed external CSS dependency, fixes a lot of consistency problems</li></ul>
0.33a | July 12, 2012 | <ul><li>Userlist now recognizes moderators -- the color is changed, they're bold, and the little chat icon that denotes them is also on the userlist in the same spot</li><li>Patched a problem with moderators being the current DJ and the star being white</li><li>Patched the userlist still populating even when disabled</li></ul>
0.3a | July 6, 2012 | <ul><li>Woot/Meh Ratios nerfed, replaced with Userlist that properly updates and doesn't have ANY problems</li><li>Clean UI with pictures instead of HTML text</li></ul>
0.2a | June 29, 2012 | <ul><li>Introduced Woot/Meh Ratios List</li></ul>
0.1a | June 6, 2012 | <ul><li>Auto Woot introduced</li><li>Basic HTML UI</li><li>Auto Queue WIP</li></ul>
