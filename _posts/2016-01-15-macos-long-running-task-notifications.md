---
layout: single
title:  "MacOS long running task notifications"
date:   2016-01-15 17:00:00
---

Very often I need to launch a long running task in terminal and switch to something else. The most frequent scenario is to perform database migrations. In grails, they run just forever, and checking terminal and switching between terminal and IDE constantly is so annoying.

I found the following solution:

{% gist f4c120d0b39d5a4f839d %}

As soon as the task gets completed, you will see a native MacOS notification bubble:

![Notification example]({{ site.url }}/images/2016-01-15/1.png){:height="123px" width="358px"}
