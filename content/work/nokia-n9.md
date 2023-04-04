+++
title = "Nokia N9, 2008-2012"
description = "Nokia's first and only Linux phone"
weight = 4

[extra]
header_image = "/work/nokia-n9.jpeg"
link_to = "https://github.com/not-matthias/apollo"
+++

The launch of the iPhone in 2007 was a watershed for Nokia. Nokia had been in the number 1 phone maker spot since 1998, and would still be for a few years, but nobody could deny (although many tried) that the iPhone was a game changer.

One of Nokia's responses was to accelerate the development of a Linux smartphone, which had been in the works for a few years as a skunkworks project within the Open Source Software Operations (OSSO) division. There was already a model in developement, the N900, but it was still a niche product and wasn't considered competitive enough. In parallel, Nokia began the development of what would become the Nokia N9, and the Meego platform it was built on.

The project was huge and complex, and got delayed many times. Meanwhile, Apple's market share was growing, and Google's newly released Android platform was getting better and better. In 2010 Nokia's new CEO, Stephen Elop, decided that Nokia would be better off with a third-party OS and scrapped both Meego and the incumbent Symbian in favor of Microsoft's Windows Phone.

Still, the N9 was almost ready by the time this decision was made, and it was easier for Nokia to release it than canceling the deals already made with suppliers, distributors etc. The [reviews](https://www.gsmarena.com/nokia_n9-review-659.php) were unanimously positive and lamented the fact that the product was a one-off, which was somewhat vindicating. More vindication came later when the Windows Phone strategy didn't pan out, and today Nokia makes nondescript Android phones. Meanwhile, many of the features of the N9 (no home button, the "swipe" gesture, always-on screen, declarative UI framework) appeared in iOS and Android many years later. Oh, what it could have been...

## What I did

I started in 2008 as the project manager (later renamed "Technical Product Owner") for the Meego address book. It was still early days and aside from a UI designer and a product manager there was no team, so the first thing I had to do was quickly contracting two developers from a local subcontracting company and get them to start prototyping some wild ideas (one of them, called the "soup" had people's faces drifiting on the screen as croutons in a soup, although the team thought it looked more like a toilet bowl).

Later the team grew and got into more focused development, but I was moved (promoted?) to manage the full portfolio of built-in applications, about 13 teams and 150 people in total counting designers and testers as well. Until we hit feature complete my job was to lead the planning activities and report the progress to management. Later, as the focus shifted to bug fixing, I was tracking and prioritizing hundreds of bugs. I also made it a point to test every daily build.   

As if building a new mobile OS with a new UI paradigm wasn't enough, one of the goals of the project was to transition the organization to agile development. I participated in process development and the application of scrum "at scale", piloting concepts that would later become part of the SaFE certification, such as release trains and product iterations. 

After the phone was launched and I was waiting to be shown the door, I created a couple of application using the Qt framework (which was Meego's development environment) and made a few hundred euros selling them on the application store :)

## What I learned

* I studied the Qt framework and really liked it. Especially QML was (is?) a great language for declarative UI programming and iOS and Android are catching up only now with SwiftUI and Jetpack Compose
* One of the goals of the project was to transform Nokia into an Agile organization. I learned a lot about applying scrum at scale, and some of the processes we implemented were ahead of their time and later ended up in the SAFE framework.
* Towards the end of the project we were managing thousands of bugs and figuring out which ones to prioritize was almost a data science problem. We used flags, charts, trends, daily triage meetings, automated crash reports and daily dog fooding to tame that matass of bugs.\
* I studied the Qt framework and really liked it. Especially QML was (is?) a great language for declarative UI programming and iOS and Android are catching up only now with SwiftUI and Jetpack Compose
* I made a few hundreds euros publishing a time tracking app on the Nokia app store :D 
* Data mining of a huge number of bugs
* Distrust in consultants, agile coaches and quality departments ("people will never be happy about the tools")

## Notes

* You can read the full story here: https://www.maquinasvirtuales.eu/the-story-of-nokia-meggo/
