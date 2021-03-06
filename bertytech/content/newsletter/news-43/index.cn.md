---
title: "Berty News #43"
date: 2020-08-21
aliases: ["/newsletter/weekly-43"]
---


# News #43

Ahoy Bertizens! ๐ดโ ๏ธ

First of all, thanks very much for all your messages over the past two weeks, all the team members really enjoyed hearing from you. 

As usual, here's the news from the team: Half of the team met at the office in Paris for a team lunch yesterday, and then threw a testing party. The rest of the team is on vacation or working remotely (say hello to Antoine if you are in Greece ๐ฌ๐ท or to Elizabeth in Canada ๐จ๐ฆ). 

Without futher ado, let's jump into News #43! 

Have a fantastic weekend!

Stay safe and cool ๐งก


## ๐ Open Source

***As you know, we're on our "road to open the beta" rush.***

We're going for gold in app stability. To this end, we're pushing hard on our replication server. This will be an optional service that will greatly improve performance. 

We're also diving deep into lifecycle management โ how (and when) to trigger the application in the background. We're continuing to move messenger store logic from JS to Go, and progressively switching from gRPC to native calls in the mobile app.

***Testing Parties***

For the first time, we were able to organize a live testing party at the office (during COVID19, no less โ all safety measures in place). We focused mainly on the stability of the app. We made contact requests, group invitations, and messages until we went cross-eyed, checking for any data lost at sea. We're pleased to report no messages were missing in action! ๐ค

![](https://i.imgur.com/EIBHUnF.png)


We noticed our group chat feature could use some attention, so we've corrected and improved group creation and invitation UX. We dredged up some interesting bugs, too. For example, one button prevents you from adding more than 3 contacts to your group. This is the kind of thing we can only find out about live.  

![](https://i.imgur.com/PIwVnfc.png)

In short, it's on the right track, don't you think? At the moment, we're exploring the design of new QR code and hoping to roll out notifications in applications ASAP.

***Berty Web Dev App***

We were also able to test the Berty Web Dev app for the first time. This is a minimalist browser developer tool that uses the latest versions of the go store and bridge. It allows us to test Berty Messenger on the back-end side. We'll tell you more in an upcoming newsletter. 

![](https://i.imgur.com/sR3uNSl.png)


## ๐ฃ๏ธ Community

* **Good First Issue & Help Wanted**: If you want to help us, we have two labels on GitHub to let you know where we need help: **Good First Issue** & **Help Wanted**. You will have our eternal gratitude and maybe some stickers if you wish. Just saying ๐

## ๐ Meet the Berty Crew

Until further notice, we are canceling all in-person events at public venues โ but we're coming soon to a screen near you! ๐ง๐ง

* October 7th, 2020: [Paris P2P #12](https://p2p.paris/en/event/monthly-12/)
* October 21-23, 2020: [PWG 2020](https://www.planetiers.com/worldgathering/)

## ๐ Blogposts

Here are the articles published since the last newsletter. Don't forget to follow us on [Twitter](https://twitter.com/berty) so you don't miss them! 

โถ๏ธ [Basic #2: Password Manager](https://berty.tech/blog/best-password-manager/)

![](https://i.imgur.com/gRtsVOE.png)


โถ๏ธ [Metadata in Mobile Messaging](https://berty.tech/blog/metadata-mobile-messaging/) 

![](https://i.imgur.com/FpHFKCF.jpg)



## โ๏ธ Recent Changes


* **Read our last weekly sync notes:**
    * [2020-08-10](https://github.com/berty/community/blob/master/meeting-notes/2020/Q3/2020-08-10--staff-team-weekly-sync.md)
    * [2020-08-17](https://github.com/berty/community/blob/master/meeting-notes/2020/Q3/2020-08-17--staff-team-weekly-sync.md)

