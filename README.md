# repository.cowduck

## _"A NoobsAndNerds joint"_

Followed Lee's youtube video [Become A Kodi Add-on Developer - 1hr Intensive Course!](https://www.youtube.com/watch?v=xVDLNbBCkLs) to set this up.

Here is the text of a
 [forum message from Lee providing  guidance](http://noobsandnerds.com/support/showthread.php?tid=17614&pid=85286#pid85286)
 on getting started...

> I would start by following the examples in the Koding section of the add-on, in fact the examples you can uncomment (the Add_Dir items shown at end of video) give a good example of how to add playable videos.
>
> What you need to do is work out how you're going to populate your lists, will you be scraping websites? If so you'll need to learn some basic regex - something which was discussed in one of those original Python Koding videos. I'm fairly sure one of the videos explained how to use regex and perform a "for loop" to create directories. For actually adding the directories just follow the format used in the template add-on, again all the documentation for Add_Dir can be found in the koding section of your template add-on.
>
> If you're just starting out then I'd recommend going through each section of that template add-on and only uncomment ONE Add_Dir item at a time and don't move onto the next one until you've read the comments and understand exactly how it's working.
>
> Once you've done that and you understand the basics I'd look into just manually adding a few playable items hardcoded in the add-on with no regex. That will give you a good understanding of how to play videos - you'll need to look at the Play_Video documentation for that but make sure you're not jumping straight into that before you understand the basics mentioned above. Try testing with something like Big Buck Bunny as your test videos - they are royalty free and direct links to those can easily be found with a simple google search.
>
> If you prefer to read the documentation in text form rather than through the add-on I'd recommend using the readme text file in the script.module.python.koding.aio add-on folder.