---
title: "Creating simple personal web site"
layout: post
author: "Prashanth Kumar"
date: 2021-11-05 -0700
permalink: /Task-9/Blog
---

## HELLO, 
This is prashanth Kumar and in this blog i am going to share my experience of Task-9 "setting up personal-website". Lets begin......

You may need to install ruby on your system before moving further. Dont go for direct installation of ruby if possible try installing through [RVM](https://www.phusionpassenger.com/library/walkthroughs/deploy/ruby/ownserver/nginx/oss/install_language_runtime.html#install-rvm). RVM will help you to switch between mutliple version fo ruby seemlessly. Now go to this [github repository](https://github.com/github/personal-website) and follow the given instructions given. 

I followed all the given instructions form the above github repository and everything went smooth. But i did also encounter some errors while doing this task and  i have listed them down with link for solution.

## ERRORS
#### *"Error: no implicit conversion of Hash into Integer"*

 => Dont not use the latest version of Ruby , I am using version 2.7.4. So better downgrade to version 2.7.0 if you are using the latest version. I got this issue cause when you install ruby using RVM you get the latest version of Ruby so i had to install ruby 2.7.x and then change it to default. 
 I solved this issue after a little bit of head-scratching google search. This is the link from where i got my issue folved => [click-on-me](https://talk.jekyllrb.com/t/error-no-implicit-conversion-of-hash-into-integer/5890/2)

----------------------------------------------------------------------------------------------------------

#### *"Installing RVM: getting error "There was an error(23)"* 
 
 => Go to this [site](https://stackoverflow.com/questions/26242712/installing-rvm-getting-error-there-was-an-error23/26370637) and the read how they have solved it. This will gave me a clear idea about the problem and i sloved it.

----------------------------------------------------------------------------------------------------------

#### *"GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data."* ####

=> This things isnt a error, its a warning but if you want to resolve this issue then you can visit [this](https://knightcodes.com/miscellaneous/2016/09/13/fix-github-metadata-error.html) site and do the given instruction. But if you working locally then this issue isnt a problem you can simply ignore this like how your girlfriend does to you...lol. You can also [visit this] link to solve the error.

----------------------------------------------------------------------------------------------------------

## ADVICE

Do not fear or panic if you encounter any problems while doing this task. Althoug the instruction given on [this git-hub-repo](https://github.com/github/personal-website) should be more than enough. I did come across many problems while installing RVM,ruby among which few i have already mentioned above but incase if you get some new error just try searching it on google. *google was my best frined throughout this task* 

----------------------------------------------------------------------------------------------------------

