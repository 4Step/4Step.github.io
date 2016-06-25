---
layout: post
title: "El Capitan vs Windows7"
date: 2016-06-24
---

As we can see, name "Windows7" itself is boring, clearly shows lack of passion towards the product. Can't they name something like "reVista" (as in "redo of Vista").

Why do I prefer Mac over Windows (El Capitan vs Windows7)? Well, here Windows is Windows& version not the latest Windows8 and Window10 and that is pretty obvious enough to say I prefer newer OS. If we are to compare windows 10 to latest Mac the overall differences maybe fewer or even down to one or two thighs such as UNIX shell and overall app integration on Mac. But since the Windows OS at work is Windows7, there are several disadvantages. Well it’s unfair to compare almost 6 year old Windows7 (using since 2010) to latest El Capitan Mac OS which is hardly a year old and is getting an update this fall.



## Modern open source software is built and supported for Mac / Linux over PC.
The following are a few programs that I use daily at work.

**1. Jekyll** - A static website built from Github pages doesn’t officially support windows.. here is what Jekyll websites states:
![No official support for windows]({{ site.url }}/assets/Jekyll_on_Windows.png) This blog is powered by [Jekyll](http://jekyllrb.com) on [Github](http://github.com) where blog posts were written in [Markdown](https://en.wikipedia.org/wiki/Markdown) and were edited in [Atom](https://atom.io/). All of this is seamless done via command line tools on Mac.

**2. GitHub**: Command line reference is one the easiest ways to operate Github and cmd on windows is not quite the same as the UNIX bash or Mac terminal in both capacity and quality. Sometimes using git cmd is unsupported as it complains on windows for powershell versions 2.0 vs 3.0. User never knows which shell version is required. Instead of dealing with this I use UNIX bash on PC, which is nearly the same as terminal on Mac but at times it crashes.

**3. TextEditor**: Modern text editors come with built-in capabilities to do sophisticated edits (like vertical, multi-selection edit and command line calls). Editors such as Atom, Sublime, TextMate are the most popular ones. However, there are significant difference between Windows7 and Mac versions as most of the Windows7 are less supported and often buggy. Example Markdown viewer for Atom often crashes.

**4. Command Line Installers**: While we try to keep up-to-date on emerging technologies to produce impressive work to keep clients surprised and advance the state-of-practice, it does require some advanced tools such as command line installer. What is command line tools: Instead of dealing with downloading a particular version of a software by going to their website, downloading, unzipping, installing and moving into applications directory and deleting the download, it is all done via command line tools in one step.

````
brew install github
brew install sqlitebrowser
brew cask install sublime-text3
````

 Future version checks and updates can also be done in one step.

````
brew update
brew upgrade sqlitebrowser
````
 Command line installers such as home brew and cask are most popular ones for Mac/UNIX/Linux OS. Unfortunately these tools are not available for Windows7 due to lack of UNIX bash integration.

**5. Modern open source programs**: (such as  Hadoop ecosystem programs, IBM Infosphere, Google Analytics API, IPython and most of its libraries) are all written for UNIX/ Linux, whether it’s distributed systems / parallel computing or it’s to run bigdata on cloud. Most of the Github is written for Linux and several of its plugins / services are heavily supported for Linux and Mac over PC. In fact if one checks any youtube video on Git training or Python or R or BigData or another computing / analysis course, most of the trainers’ screen show Mac and tutorials shortcuts are geared for Mac / Linux over PC. In most of these tutorials, there is a heavy mentioning of Mac shortcuts and tips. Although this is not a my point to argue for Mac but it does prove that modern languages and programs are well supported on Mac. Ruby, RubyGems, Ruby on Rails are another example of less supported modern language on Windows7 . This is true even for newer versions of windows like (win 8 or win10).




## Better hardware and Software Integrations
**1. Better Configuration**: Mac Book without any doubt comes with very nice and advanced hardware. I own a MacBook for about 6 years and has better hardware configuration than my PB work laptop which was 4 years old and died last week. Additionally, I had challenges connecting to newer routers with the PB PC laptops over my MacBook Pro and the reason being the low end wireless cards couldn’t catch latest frequencies.

**2. Battery**: Again, my 6 year old MacBook is the proof that it has better batter life than my two work PCs which lasted less than 3 years befogging running into battery issues. Apart from this, single charge on Mac battery last longer than pc battery.

**3. Built-in Software**: Most of the program software for Mac is either already installed such as python and gawk or easy to install with command line installers such as home brew. Installing programs on windows is not a nightmare, for example [pandoc](http://pandoc.org/) is a program to convert word document to markdown or html, that takes a challenge to install, find and run on windows. Also to mention it takes lot of man hours to constantly updating third party installations on windows as windows lack something like home brew where all packages can be updated.

**4. Integration onto devices**: Most of the apps are cross-platforms or cross-devices, meaning I can have a textPad app on MacBook, iPad and iPhone and start making notes on one device but can also edit on other devices. For instance I cannot write of all the differences between Mac and PC in one take and so I started this on my MacBook, and while I am walking I added a point or two to this edition from my iPhone and then when I relaxing on my patio I added couple of more points via iPad. I was able to do this as this app is available on all the devices (pre-installed) and is seamlessly synced via cloud account (gmail). Apps such as this makes taking notes lot easier and improves efficiency by not losing the thought.

I started writing this topic in notes (MAC), for easy editing. Below is the screenshot of the notes under progress.
![Mac Notes]({{ site.url }}/assets/Mac_over_windows.png)




## Cross platform development
Our industry has not moved into 21st century yet as we are heavily dependent on programs and practices of the previous decades. For example, we still use
MS office for documentation, which hasn’t improved in several years (lacks markdown and quick html rendering) and the only version control is to use track changes which is clumsy and gets cluttered if more than two people work on it. Hey, we are writing 120 page technical document and 200 page user’s guide with lots of pictures, tables and graphs and there are lots of people who are contributing to this document including clients. We do need to move away fro just word documents. Similar things could be said about Excel’s lack of functionality to save to JSON or XML formats. But the new generation documents are all up in cloud, managed through web-pages and version controls.

In this day and year, we don’t need to rely on just doing work on one platform since that’s only where our work actual runs (referring to exclusive based windows programs). The new generation is all about cross-platform development and web-based mobile applications. I should be able to edit a wiki-page [NERPM43 wiki page](https://github.com/4Step/NERPM43/releases) or reply to clients comment or fix an issue [client comments](https://github.com/4Step/NERPM43/issues/8) for the user’s guide I wrote while I am sipping my morning coffee rather than come-in to the office and work exclusive on a word document that is saved only on the PB intranet. Working on newer windows (win10) is fine but since we are provided with win7, these things are not well integrated, making my day go worse in trying to get these things workings (sometime a webpage may have trouble integrating well with the text editor, sometimes it doesn’t sync to cloud, sometimes UNIX terminal crashes, sometimes wifi is not connected due to low end old wifi-card and the list goes on).

Increase ability to write programs in open source framework such as python or R or even newer C++ which works on multiple platforms. Unfortunately leading travel demand modeling softwares CUBE and TransCAD are still windows only applications keeping the entire practice at bay. However the two vendors are much aware of the trend and may unveil their Mac / Linux versions anytime and at that point we don’t want to be the late adopters. It’s not as simple as get a Mac install Mac version and build the program. This takes several months of practice ignorer to efficient build custom applications that are of impressive quality.
