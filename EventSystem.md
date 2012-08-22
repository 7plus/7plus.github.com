---
layout: page
title: Event System
---
{% include JB/setup %}
This system allows to combine many different submodules (over 100!) to create the desired behavior.

Here are some examples that show how an event can get executed:
* By pressing a hotkey
* By moving your mouse in a screen corner
* Through file/directory context menu entries created with 7plus
* On a timed schedule
* When a button in the Explorer band bar (Win Vista / 7 only) added by 7plus is clicked
* When a file or directory changes

For each event it's possible to add conditions that limit the execution of the event to a specific context. These include among others:
* Restricting the event to specific active windows or focused controls
* Requiring that a specific file is selected or Explorer is in a specific path
* Restricting the event to an active (non-)fullscreen window
* Requiring that the mouse is over a window or control

An event can execute a list of actions such as:
* Running a program/file/folder/URL
* Showing a message
* Activating/Closing a window
* Sending key or mouse input
* Setting current path or selected files on various windows (such as Explorer)
* Writing text to clipboard or to a file
* Uploading a file to FTP or [ImgUr.com](http://www.imgur.com)
* Trigger an [if this then that](http://www.ifttt.com) recipe
* Send an email
* Take a screenshot
* Shutdown the PC
* Copy/Move/Delete files