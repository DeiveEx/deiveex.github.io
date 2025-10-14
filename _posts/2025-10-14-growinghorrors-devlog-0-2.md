---
title:  "Growing Horrors - Devlog 0 - Part 2"
date:   2025-10-14 12:00:00-0000
categories: announcement my-games development games devlog growing-horrors
header:
    overlay_image: /assets/images/GrowingHorrors/Logo_V1_color_Negative.png
    overlay_filter: 0.7
show_overlay_excerpt: true
excerpt: Rising Tide Challenge!
---

Hey everyone!

What's this? Devlog 0 - PART 2?? What the hell is that?

Well, I kinda figured that I should probably talk a bit about the development of the Rising Tide Challenge trailer before talking about the actual game development, and it didn't feel right to call that as "Devlog 1", so... Here we are with Part 2.

# The Challenge

So, what is the Rising Tide Challenge and why did I decide to participate?

I heard about it when I've received an email from the Global Game Jam, where they said there was this new challenge where game developers could get investment by just providing a trailer for their game.

A full investment for just a trailer? That sounded quite interesting.

I went to their site and started reading about it. They were promising up to 300k in investment for 20 winners, with 10 winners being decided by the public and 10 being decide by "industry expert" judges.

This sounded like the perfect oportunity to test my idea: making a trailer is much easier than making a playable prototype since I can fake a lot of things and, even if we didn't win, I would get direct feedback about how "desirable" a game like this would be! So, I presented the challenge and my idea to some friends and we decided to participate.

# The Development

I was unenployed at the time, so I had lots of free time to work on it. I also knew my friends didn't have this luxury, being employed and all, so I knew since the beggining that most of the work would fall on my back. And this was kinda expected, since it was my idea, after all.

I actually had the basic script for the trailer mostly done even before knowing about the challenge. I found it a pretty good exercise to think about how well you can present your game in a trailer even before doing any development for it. It helps decide the "selling points" of the game, since that's what you wanna show in the trailer. I had to just write it in a way that friends could use it as a guide for what needed to be done.

I guess you could say I was the "director" for the trailer. I don't think I ever directed anything. Thankully, in our team we have aperson with experience creating small movies, so they helped me a bit. [The guys at BOG also provided a nice livestream explaining what makes a good trailer](https://blueoceangames.com/resources/posts/advice-from-trailer-expert-derek).

{% include figure popup=true image_path="\assets\images\GrowingHorrors\rtc_shot_list.png" alt="Our shot list" caption="Our shot list" %}

One of the requirements for the trailer is that most of it, if not all, should be created using in-engine footage, so that made my life easier since that was exacyly what I was planning on doing. That said, I had this idea only on paper, aside from a few systems, I hadn't developed anything for it yet. The hundreds of Humble Bundle assets I've been gathering over the years would finally have some use!

I have a few very specific things in mind I wanted to do: First, I wanted to use a "3D Pixel Art" Style. Not only I find it very cool, but I believe it also allows you to merge different 3D assets more easily, since a lot of detail is lost when dowscaling the resolution.

{% include figure popup=true image_path="\assets\images\GrowingHorrors\rtc_references.png" alt="Some of the references I gathered" caption="Some of the references I gathered" %}

Secondly, I wanted to a tell a small history, progressively showing how more and more weird things start to happen the longer you play (hence why the name GROWING Horrors). So, I had this idea of separating the trailer in "days", and each day shows more and more weird things.

And finally, if you search about good practices when making a trailer for anything, one thing they'll always tell you is how you should start with a bang, because most people will simply skip your entire trailer if the first few seconds is not interesting. So I had this idea of "planting" some mystery at the start, just to reveal what it was at the end of the trailer.

So, with that, I've created a new Unity Project and we started development.

Like I mentioned before, I had nothing of the game developed, so most things in the trailer are just "cutscenes" created using Unity's Timeline System. It's pretty hand for this kind of things. I still developed a few scripts, like one to use certain tools animations and another to modify the tilemap dinamically so I could show things like tiling the ground or watering seeds. I've divided each shot of the trailer into a scene with their equivalent Timeline. I do control the character from time to time though (like the show where you water the plants).

{% include figure popup=true image_path="\assets\images\GrowingHorrors\rtx_unity.png" alt="Behold the Unity mess" caption="Behold the Unity mess" %}

In total we were a team of five people. Six if you include my girlfriend, which didn't directly work on the trailer but provided some of the character concepts

- Two of them (Deivede and Valentina) were mostly resposible for some custom 3D models (the farmer character, and some mutant plants), with Valentina also being responsible for the Character portraits (which looks very cool!).
- Victor created the awesome game logo (seriously, I love it!) and helped a bit with the video editing.
- Lucas, which is the person I know with the most Shader Development knowledge, created the Pixel Art Shader, which was crucial for the final look.
- And I was responsible for actually building things in Unity and recording everything, which includes finding assets, like the environment models and sounds, as well as some video editting. Ah, yeah, I was also responsible for the animations, which includes a mix of Mixamo animations with manual editing in Blender.

It was a LOT of work, and we actually published the final trailer in the last day. But overall, I think the result was pretty close to what I envisioned. Shoutout to [Asset Inventory](https://assetstore.unity.com/packages/tools/utilities/asset-inventory-3-308224) and the [Unity Recorder package](https://docs.unity3d.com/Packages/com.unity.recorder@5.1/manual/index.html), because they made my life a LOT easier.

# The Results

After the publishing period ended, there was a 2 week voting period. I voted for games everyday, and I just saw my own game once. I think the voting system was pretty good, putting 2 games next to each other and making you decide which one you think is best. Sounds like a pretty fair way of voting to me.

There were some crazy good games there, some of which were clearly in development for years already. This made me lose a bit of hope of having any chance of winning, specially considering there were more than 1000 entries in total (around 200 didn't fit the rules and were disclasified, but there were still 800 which were valid).

But I still had hope. If you've ever watched Aggretusko before, there's a quote where they say something like "If you put a cactus in a desert, no one will notice, but if you put a sea ​​urchin in the desert, everyone will notice". Well, I like to think I was the Sea Urchin. Not necessarily the best game in there, but definitely something different.

After two weeks of voting, the results were revealed. And lo and behold, our trailer created from scratch in a month won the judges pick!

{% include figure popup=true image_path="/assets/images/misc/RisingTideWinners.png" alt="Rising Tide Challenge Winners by Judge's pick" caption="Rising Tide Challenge Winners by Judge's pick" %}

We got #205 in the public voting, which was good, but personally I was hoping to be at below #100. But that's okay! I mean, again, some of these projects are in development for years, and you can see the work in their trailers. I also got some feedback about my trailer that I agree with. Still, being selected by the judges was huge!

# Final Thoughts

Well, there you go, that's how the development for the trailer went. If you haven't watched the trailer itself yet, just check it below.

<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1fDa9FvGg?si=VYO3c79dQa83VLiy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I'm pretty impressed with the result, and while the BOG contract thing was a bit of a bummer, all this endeavor gave me the strenght to try and make this thing happen for real. So... I guess we'll see what happens in the future!

Next it'll be a more development focused devlog, I swear!