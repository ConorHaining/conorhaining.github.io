---
layout: post
title: Being a Hackathon Particpant
header-image: /images/HackathonParticpant/HackathonPlaybookParticipantTitle.jpg
header-alt: Flying the University of Dundee flag while at GUTS 2018
category: Hackathon Playbook
summary: I've been very fortunate to be heavily involved in hackathon culture while I was a student and into my full time job. I've been able to act as an organiser, a participant and as a corporate sponsor. In this three part series I'm documenting the processes and ideas I follow to contribute to this community. In part one, I'm discussing how I've been a participant and how I've taken on challenges across Scotland and Europe.
---

I've been very fortunate to be heavily involved in hackathon culture while I was a student and into my full time job. I've been able to act as an organiser, a participant and as a corporate sponsor. In this three part series I'm documenting the processes and ideas I follow to contribute to this community. In part one, I'm discussing how I've been a participant and how I've taken on challenges across Scotland and Europe.

# Finding a hackathon

In my experience, hackathons tend to broadly fall into one of three categories. University organised events are typically put together by a computer science or tech society with the committee members organising it alongside their studies. Then there is what I call "Major Hackathons"  which are open to students and those early in their career but are more polished events that have the backing of dedicated organisers. Finally there are corporate organised events which have dedicated organisers and typically one sponsor who foots the bill for the entire event. Knowing the type of hackathon you are attending sets your own expectations for the types of challenges and organisations that are going to be be present. I don't have any personal experience with corporate sponsored events but I would assume that for the most part, what I'm going to lay out here is applicable to all three types of events.

If you're looking for places to pick up your first hackathon, here's some places to start. Firstly, your local university's tech or compsci societies are likely to host one every year so that's a solid place to start. Even if you're not a university student, it's rare for you to be disqualified unless you're already an established engineer. Following that, neighbouring universities are also solid places to checkout. They usually have Facebook pages and sometimes websites. Then there is MLH, Major League Hacking, who are an organisation which support student hackathons across the world by running leagues in North America, Europe, and Asia-Pacific. I'll come back to MLH more in the organiser section, but while they are a great and well intentioned organisation, they are very focused on North America and have a tendency to overlook smaller events in Europe.

# What you should be looking for

First and foremost, decide what you want to get out of the event. There is plenty of things to gain from hackathon and here are the two things I often looked to get out of it.

Organisations typically sponsor events for one of two reason, either it's evangelism for a product that they're trying to sell to developers (think companies like Twilio or Github) but it's more common that a company is looking to hire junior/graduate engineers. This is a great chance to meet enthusiastic engineers who may have only recently entered the field. Even if you don't want to join the company they're at I've found most people are happy to talk shop. It's worth quickly pointing out that at some hackathons, particularly the larger ones, there are sometimes companies who are looking to acquire intellectual property and create startups or spinouts but I've never had any experience with that.

There are few opportunities for you to dedicate some time to picking up something new and just flying with it. Hackathon projects can be a throwaway adventure and still a great learning experience. I've had a chance to play with Unity and it's VR capabilities when creating a balloon popping game, my first ever project. The first time I used NodeJS was at a hackathon, as well as dipping into machine learning with Jupiter notebooks.

# Preparing yourself

Most hackathons are rarely further a short bus or train trip, but if you're looking to venture further afield then I'd highly encourage you to do so. I've been very lucky to visit Eindhoven and Helsinki for hackathons. Some offer travel reimbursement which depends on the distance you're travelling. If an event doesn't offer reimbursement and you don't think you could make it otherwise, it's worth contacting them to find out if they can support you in some form.

One thing I can't stress enough, if you've travelled internationally for an event, you cannot get by on the sleeping arrangements at the event. You will need to get yourself a proper bed to sleep in at some point. Also, sometimes there is no place to put your luggage, it just becomes a mess.

If you're packing a bag to go, make sure you've got a change of clothes and some toiletries to see you through the weekend. You may be fortunate enough to either be close to home where you can nip home and shower or you're at a venue with those facilities. Make sure you've got all the big bandwidth items such as code editors, SDKs, and other bits of software you might think you'll need to enable your hack, Wifi going down or being deathly slow is a common trend within the first hour.

# Hacking Begins

I've found venues to come in all shapes and sizes. I've hacked in small breakout areas on uni campuses, [to former factory floors for Phillips](https://conorhaining.com/posts/HEX-2018/). Scoping out the venue is worthwhile, finding a good spot can be make or break for the weekend. Organisers and sponsors enjoy wandering around to see what hackers are up to so if you're quick enough you can use the opportunity to do some very early project discovery, and use it to clarify you are going in the right direction for the hack.

There will typically be a Slack workspace or a Discord for you to join, it's important to get on this early so you'll see announcements from the organisers for when food arrives and a chance to interact with the sponsors who usually have their own channel. It's a great place to ask questions when you have problems or to exercise your shitposting skills.

You will need a crack team to successfully take on any challenge. I've always arrived at an event with friends as a team but if you're not able to gather people beforehand then there are usually opportunities setup for you to find team mates. Hacking will often kick off around lunch, but I have known events to kick off after dinner, in either case it's usually proceeding a mealtime which gives you time to mingle and try find people or existing teams. It's also another reason to join the Slack/Discord so you can broadcast your enthusiasm while looking for a team.

Now you've got your team, get a git repo setup, add people as collaborators and setup some scaffolding for what you think you might need.

## Idea Planning

You should subtract 8 hours for rest (whether you use it or not is another matter) to give you a realistic estimate of how long you have to complete your hack. Once you know how long you have, you can start to think about the scope of your solution. There is no one-size-fits-all approach to hackathon ideas but there are some things I think can give you an edge.

Ensure that you truly understand the challenge you are taking on, some challenges require proper research and reading before you can properly develop a solution. When at [Junction](https://hackjunction.com/) we took on a challenge to detect a [SS7 attack](https://www.theguardian.com/technology/2016/apr/19/ss7-hack-explained-mobile-phone-vulnerability-snooping-texts-calls) in a stream of pcap data, which is the format of SMS traffic over a real mobile network. The challenge came with a length document of background research which we skim read and dived into what we thought was the solution. The result of this was a failed hack. We didn't understand what we should be looking for, the AI model we created was incorrect and by the time we realised what was going wrong, it was too late to retrain the model. We declared it a failure and went to explore Helsinki instead.

Your hack should seek to meet the challenge in the smallest and cleverest way possible. For fun hacks that are either purposefully silly or are game based, you're seeking to impress or enthuse the judges of the challenge. I like trying to find points where hacks can be funny. While at [RGUHack](https://rguhack.uk/) in 2017, we created a ball pit VR game modelled on the open space theatre that was being used for the venue. This advice can definitely extend to more serious challenges as well, when at [GUTS](https://gutechsoc.com/hackathon) in 2018 we created a call center application for a challenge to perform analysis on some audio stream but we used the [Cantina Band](https://www.youtube.com/watch?v=sHD-knhS6es) as our hold music before you get connected. Both of these things gave us an edge and I think made us more memorable.

Don't feel like you need to knock it out the park or be a superstar coder to create a good hack, when we created the VR balloon pit game, that was our team's first time using VR or Unity. It's impressive to see teams take on something absolutely new to them and still produce a product. It makes that win all the more rewarding and sweeter.

# Hacking

There is no time to set out a comprehensive system architecture, so if you will working across different parts of a system, you must be crystal clear about what your expect and return for the functionality you are working on. You'll be constantly communicating about what you're doing, and don't be upset if somebody hasn't registered what you're doing, there is a lot going on and it's easy for things to fall out of a persons mind. You'll be sharing verbally but you should always be pushing your code frequently so everyone has access to it. Don't be afraid to get help from your team, mentors, or anybody really. Sure, a hackathon is a competition, but the learning experience is the key thing to remember. Most people will be glad to show off some skill or thing they know, as long as people are friendly and grateful then everyone becomes better of.

Keep it simple, stupid. While hacking it's very easy to start thinking of things that can enhance your project before you've completed what you're doing, in the real world this is scope creep. Write these ideas down at the very least and come back to them when you're confident with your actual solution. It's very simple of projects to spiral out of control as people start wanting to show off - which is great - but it's not possible to do this without a solid foundation. Everyone in the team needs to be cautious and concious of this, if you start dismissing other peoples feature ideas it has to be legitimately to stop scope creep.

It is vital to get some rest. It's a common joke and mantra about continuously coding throughout the night like you're some kind of all powerful machine. You are not the [Duracell Bunny](https://www.youtube.com/watch?v=4AZg11VPKow), no matter what you think, you need the time to stop, put your mind elsewhere and recharge. Even if you are capable of staying awake for the duration of the event, the hangover from that lasts for days and days and is hellish. For your own sake don't do this.

# Final Countdown

As you approach the end of the hacking period, there is a couple of administrative items you need to have ready. Many events ask you to publish your hack onto [Devpost](https://devpost.com/) which enables judging and showcasing. Often if you neglect to do this, you will not qualify for judging and the time you've spent writing code won't receive recognition.

Give some consideration to how you will show off your work. As a general rule of thumb, you shouldn't have any slides unless there's tangible to your hack. Show off what you've done, what you'd like it to do with it in the future, and where applicable, give the judges a chance to use it. If you've got something unique about your hack, demo that to the judges first since there is often very little time! In the hack at GUTS mentioned previously, we made our judges call our hack to see it work live in from of them. Remove as much risk as you can from your demo, so you may need to fake a couple of items but since you can guide people through your narrative you can often get away with this. Document what you've learned and make sure your judges know this as well. One of the secondary judging criteria is enthusiasm and showing off your willingness to learn is endearing to see as a judge.

Hackathons are a fun learning experience, and it's a sandbox for you to try out new tech and to expand your learning. You also meet wonderful like minded people who you can share this experience with. If you are early in your career, hackathon projects give you an edge against candidates with similar academic background. I interviewed for my current job after winning at a hackathon and was able to show off my experiences and learnings from that.

Next time I'll go through what it takes to plan and organise your own hackathon for your community as well as what I've observed at other events to compare and contrast.