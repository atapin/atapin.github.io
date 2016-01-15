---
layout: post
title:  "MacOS long running task notifications"
date:   2016-15-01 17:00:00
categories: macos bash zsh til
---

Very often I need to launch a long running task in terminal and switch to something else. The most frequent scenario is to perform database migrations. In grails, they run just forever, and checking terminal and switching between terminal and IDE constantly is just so annoying.

I found the following solution:

{% gist f4c120d0b39d5a4f839d %}