---
title: "Week Five: Imaginary Friends"
date: 2020-04-13T11:27:14-04:00
draft: false
toc: false
images:
tags: 
  - agency
  - weekly standups
---

*See all the weekly standups [here](/tags/weekly-standups/).*

Five weeks down! By the end of this blog post, you’ll learn some ARKit, how to write a pitch to a hypothetical customer, and how to maximize your productivity. Let’s get it.


## Playing Around with ARKit 

This week I decided to step back from Spark AR and look at the AR space more broadly. I had already tried to use Unity’s AR Foundation w/ Vuforia a bit, but I was disappointed by the build workflow (*”build” in this context means deploying an app to a device*). I didn’t know much about ARCore (Android) or ARKit (iOS), so I didn’t have too much of a preference. The universe ended up deciding for me since I only own one AR compatible device, my iPad, so it made the choice of trying [ARKit](https://developer.apple.com/augmented-reality/) straightforward. 

My first ambition was to create an AR experience that could track an image and play a video. I’ve always been intrigued by the idea of turning images into “links”, and giving them more details than their 2D facade lets on.

After spending **hours** trying to fix the XCode bugs I was running into, I was finally able to piece together the components I needed to make the experience you see below. 

{{< instagram B-zT2aHjkbX >}}

It's freeing to be able to have full control over what I build (SparkAR can be limiting at times) and I’m excited to deep dive this technology in the next few weeks and see where I can get.

*P.S. If you run into `code signing` issues, make sure to **unlock and lock your Keychain** and set each key to **Use System Defaults** NOT **Always Trust**. This took me a while to figure out.*

## Imaginary Customers (or Friends)

I’ve been watching this [Teatime with GaryVee](https://www.youtube.com/watch?v=mlw_3BLoeJA) series on YouTube. 

It’s a series where people can call Gary Vaynerchuck and ask questions about business and life on livestream. Gary then throws “Gary-isms” at people, some of which I find very helpful.

Aside from getting me to start thinking about selling some stuff I don’t use on Ebay, Gary said something that really stuck with me. He reminded the viewers that you don’t need to be closing actual deals with customers to be creating value for people. Thanks to the power of imagination, we can **create** our ideal customer and solve a problem for them. Wow! 

This method doesn’t map perfectly onto reality. There’s no way to know what pain points a client truly wants to solve, what their budget looks like, and what their time frame is to solve them. But these thought experiments are **fun**. I get to put my head into the mind of another, and to imagine I’m on stage at a pitch meeting.

And so, I started the “If I Were” series. The series examines three (or so) ideas I would implement as an AR creator for different fields. This is a very fun and exciting process, and I’m glad I found something that feels like deliberate practice, even in a time where businesses aren’t really looking to try new tech out.

- [If I Were a Music Festival](https://www.sharingfiction.com/posts/if-i-were-a-music-festival/)
- [If I Were a Visual Artist](https://www.sharingfiction.com/posts/if-i-were-a-visual-artist/)

## How to Stay Productive During Quarantine

I’ve seen a lot of repeated, unresearched information on the Internet about “maximal productivity during quarantine”. Even worse, I’ve seen a lot of **mis**information on the subject as well. 

Some people use clever hooks, others use acronyms, but **almost all miss the point**.

**Productivity is subjective**. The *definition* of “productive” of varies from person to person, so why would you take the advice of someone who **isn’t you** on how to be productive? Let me explain.

In a society that *only* grows rutabagas, one can be “more productive” by planting one more rutabaga than their neighbor. But what if your neighbor grows carrots? Or apples? In the modern day world, every person is doing a different job. A productive carpenter and a productive dentist are two **completely** different things, as they have entirely different goals.

To find **your** version of productive, you must first define what **productivity means to you**.
No one else lives within your mind, so no one else can tell how this works. It’s a solo quest.

That said, I do agree that there are constants in the productivity equation.

There are 24 hours in the day for every person on this planet. Everyone must fulfill their biological functions (sleep, eat, drink water) or they will die. To produce is better than to consume (generally, that is; not taking into account externalities). 

These constants serve as a good framework to inform you on how to optimize your time, but they are only a **framework**.

So the next time someone makes you feel guilty for not reading *Nietzche* and modeling for your photoshoot at *Forbes* while completing your 15 mile 6AM jog, remind yourself **it doesn’t matter**. 

You are only in competition with yourself.

## AR Learnings

- ARKit has an `ARResource` folder where you keep your images to track. Make sure you specify the real world size of the object!
- XCode Developer Licenses are tricky. Make sure your `keychain` is set to `Use System Default` instead of `Always Trust`
- Videos and Image Assets can be added directly to your bundle (and they should, trust me, don’t try with URLs; its super slow)

## A-Ha Business Moments

- Be agile, always. Resistance to change hurts you in the long run, as change is inescapable.
- Separate your emotions from your business ambitions. Ego can quickly collapse a good idea.
- People are busy. Convey your vision [as quickly as possible](https://www.youtube.com/watch?v=Unzc731iCUY).


Thanks for reading, stay safe out there.

