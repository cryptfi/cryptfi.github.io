## Archiving Content

I was originally going to compile a list of OSINT Resources, but that's already been done in several places, so I decided i'd cover archiving content.

If you're interested in some OSINT Lists here it is:

 1. [OSINT Framework](http://osintframework.com)
 2. [Technisette](https://start.me/p/m6XQ08/osint)
 3. [OSINT Resources ](https://brokemy.network/osint-resources/)
 4. [Awesome OSINT](https://github.com/jivoi/awesome-osint)

Introducing our first tool 'ArchiveNow':

ArchiveNow is  an opensource tool, which can be installed via pip, it allows you to archive websites via the command line.

To install and use it we'll do:
~~~
terminal@x:/mnt$ sudo pip install archivenow
terminal@x:/mnt$ archivenow --ia --is [YOUR-URL]
~~~
If you want to archive a list of sites:
~~~
import os 
f = open('list.txt','r') 
for i in f:
    archive = ("archivenow --is " + i) os.system(archive) 
f.close()
~~~
You can also run it on localhost as a web service:
~~~
terminal@x:~$ archivenow --server --host localhost --port 11111
 * Running on http://localhost:11111/ (Press CTRL+C to quit)
~~~
![enter image description here](https://i.imgur.com/xPgHJgZ.png)

You can check their [Github](https://github.com/oduwsdl/archivenow) for more information.

### Web Based Archival

If you don't want to archive sites from the command line, there's a couple of web based archive sites that you can use in your browser. 

 1. [archive.fo](https://archive.fo/) | Public
 2. [web.archive.org](http://web.archive.org/) | Public
 3. [perma.cc](https://perma.cc/) | Login Required
 4. [webrecorder.io](https://webrecorder.io/) | Public

Most of these are self explanatory, pop a URL in and press the button.

### Alternative website archiving


Another way of archiving a page is to just take a full page screenshot, there's a multitude of ways to do this, from chrome extensions to the command line to downloading a picture from [archive.is](https://archive.is). 

*Chrome Extension* | [Github](https://github.com/mrcoles/full-page-screen-capture-chrome-extension) / [Chrome Store](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)

*Snapito (Web Tool)* | [Site](https://snapito.com/)

**Extra**

*Archive Today Bookmark* - You could also bookmark
 ~~~
void(open('https://archive.today/?run=1&url='+encodeURIComponent(document.location)))
~~~
now when you click on it in your bookmark bar your current page will be archived to [archive.is](https://archive.is/).

*Twitter* | You can now tag [@archive_tweet](https://twitter.com/archive_tweet) in a reply to any tweet in order to save an archive to both [archive.is](https://archive.is) and [archive.org](https://archive.org)

 
