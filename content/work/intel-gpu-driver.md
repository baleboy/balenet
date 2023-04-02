+++
title = "Linux driver for Intel GPUs, 2018-2020"
description = "Open source development of Linux driver for Intel's integrated and discrete GPU" 
weight = 7

[extra]
header_image = "work/intel-xe.jpg"
+++

I joined Intel's Graphics Software Center in April 2018 to manage a team developing the [Linux graphics driver for Intel GPUs](https://www.intel.com/content/www/us/en/develop/documentation/intel-graphics-for-linux-programmers-reference-guide/top.html). The driver was fully open source and developed mostly in the open and up to that point was supporting Intel's line of integrated GPUs, with Chromebooks and Linux laptops as the main targets. However at that time Intel was getting back to the discrete GPU market and the Linux driver was very important for data center customers, so the priority of the project increased as well as attention from management.

The GPUs (Intel Arc Alchemist, Ponte Vecchio) are out in the market now and supported by Linux, which is something I am very proud of although I left before any of those products were released, to get out of the corporate world and try out what life in a start-up looks like.

## What I did

I managed a team of 8 made of some very senior and some less senior engineers, all of them experienced and very smart. Aside from the usual people management tasks (1:1s, performance reviews, hiring, target setting, career development) I spent a considerable amount of time on project management tasks: communicating with other teams, reporting to management and keeping track of our commitments.

I think I was able to foster a good team spirit and integrating even the most stubborn open source devotees with the rest of the company. I'm particularly proud of the people I was able to promote, which took a lot of time not just during the performance review period, but also during the year in terms of highlighting people's achievements and ensuring that when the performance review did come, those who made the final approval knew what each individual had done and why they should be promoted.

## What I learned

After many years of project management, this was my first stint as an engineering manager and I loved it. I worked with the best engineers I have ever met, some of them truly 10 or 20x and I helped other members of the team grow and be promoted. I found true satisfaction in this, and the best memory I have taken from that time was when I left and one of my reports thanked me for "being an excellent manager, the best I've had, and I've had a few". As far as I know, they still use the name "teambale" for their IRC channel :)

Technically this was the most challenging job I've ever had. The Linux kernel is not something you get into easily, and neither is graphics (although at the kernel level there wasn't much graphics involved, mostly managing buffers and threads). I really tried to get hands-on, but it was too much. I learned to admit my shortcomings and rely on my colleagues who knew much more than me. I still tried to learn, and discovered great books like Mike Abrash's Graphics Black Book and Fabien Sanglaard Game Engine Black Book series.

I didn't like the open source politics. There was a lot of it, including backstabbing. Open source should be about technical excellence but in the end it's still about people.

One painful lesson was that I should have used the trial period better. Another one was to estimate things without the team.

I worked with Chris!

## Notes

- NVidia eventually released their driver as open source, whcih is ironic given that inside my group at Intel Nvidia was taken as the prime example as to why we shouldn't do open source. The devil is in the details though, and most of NVidia's driver is inside proprietary firmware, which was also Intel's strategy with the GuC.

- It was impossible to say the words "Intel" and "Discrete Graphics" without someone reminding of Larrabee. Larrabee was a previous attempt by Intel to enter the discrete graphics market (which it had left after the xx) and was widely considered to be a great architecture, however it was canned shortly before launch and many people are still sore about it. In retrospect it's like Intel's N9.