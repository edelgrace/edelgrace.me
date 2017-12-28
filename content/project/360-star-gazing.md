---
title: "360 Star Gazing"
slug: "360 Star Gazing"
type: "project"
date: 2017-11-11T23:25:12-06:00
featured_image: "http://res.cloudinary.com/dvozrk6m8/image/upload/v1514417528/360thumbnail_ontyne.png"
snippet: "A Google Cardboard 360 Video experience where users can find constellations in the sky."
---

{{< load-photoswipe >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510672152/Screenshot_2017-11-13_20.23.29_myhubk.png" title="Sample screenshot" class="img-responsive" >}}

* [Source code](https://my.pcloud.com/publink/show?code=XZSU807ZaRVQFCmBaUV8nRNA7VJ3nmBkX7dX)
* [Download](https://my.pcloud.com/publink/show?code=XZNx807ZqMY2jy203mz3boJEVNgXYS3Ap2kV)
* [How to Run](https://github.com/edelgrace/message-ring/blob/master/README.md)

# The "Problem"

When was the last time you looked up at the stars? If you're like me and live in a big city, you might not even remember when the last time you could properly see a star that wasn't the sun. Of course there may be astronomy enthusiasts out there who make a hobby out of looking at the night sky but for the rest of us, we're wannabe casual star gazers. Even if the night sky was readily available to all of us at all times, some of us might now even know what we're looking at. This is where *360 Star Gazing* comes in.

# The Solution

{{<youtube 317NmLQjfcU>}}

This project is essentially a virtual planetarium that is guided by a narrator who explains different constellations to you as you find them. The user can look around at a 360 time lapse of the night sky and when their gaze falls on a constellation, the constellation is highlighted and our text-to-voice David Attenborough knock-off will give a little spiel about the mythology behind said constellation.

What I wanted the most was to emphasize a sense of wonder as you gazed up at the stars. The possibilities are endless. My hope is that as you discover the constellations, you are reminded of the beauty of the stars and the power human of imagination.

## Why 360 Video?

The way I justified the use of 360 video is the fact that there is a large search space that is the night sky, which envelopes you in all directions. The user must look around them as there may be constellations behind, above, and in front of them.

# The Process

## Figuring out the Problem Space

I always knew Google Cardboard was in some sense related to virtual reality but when given this problem I initially focused on augmented reality. My first couple of ideas were duds in this sense as we were to focus on 360 video rather than placing virtual objects into our world.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850865/New_Doc_2017-12-09_27_sp34yd.jpg" title="Real time graffiti">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850863/New_Doc_2017-12-09_28_dafsiz.jpg" title="Image recognizer">}}

{{< /gallery >}}

## Beginning Ideation

After talking to some people and looking at 360 videos, I finally got a grasp on what the project should consist of. I focused a lot on simulators and guided tours. In my mind, one of the main attractions of immersive 360 video was having the ability to have experiences you've never had before in a (hopefully) safe environment. 

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850867/New_Doc_2017-12-09_32_gxld3o.jpg" title="Eavesdrop on patients in a waiting room">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850866/New_Doc_2017-12-09_30_ki5jkt.jpg" title="Meditation guide">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850868/New_Doc_2017-12-09_33_wbart2.jpg" title="Good vs bad thought simulator">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850872/New_Doc_2017-12-09_36_ygpt1k.jpg" title="Cat snek">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850866/New_Doc_2017-12-09_31_fmnee9.jpg" title="Memory lane">}}

{{< /gallery >}}

## Main Sketches

Out of all the sketches that I drew, I was most drawn to these sketches below.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850868/New_Doc_2017-12-09_29_pzdrja.jpg" title="Therapy workshop">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850872/New_Doc_2017-12-09_35_akrp6p.jpg" title="Lifeguard Simulator">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850870/New_Doc_2017-12-09_37_lb3cmu.jpg" title="Constellation finder">}}

{{< /gallery >}}

## Feedback/More Sketching

When talking to others about my ideas, a lot of people expressed interest in each of them. However, I had to think a little more reaslitically about the feasability of my ideas. I knew that I didn't have enough time to film my own scenes and after some searching around, I found it was near impossible to find any 360 videos of people drowning. There were, however, plenty videos of scenary timelapses.

While coming up with different ideas, I wanted to focus on the discovery aspect of the star constellations and different ways the video could play out with the constellations.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850870/New_Doc_2017-12-09_38_wjiakl.jpg" title="Star gazing but with cloud shapes">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850872/New_Doc_2017-12-09_39_irh9xm.jpg" title="Different storyline structures">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850871/New_Doc_2017-12-09_40_ubx4sa.jpg" title="Finger pointing gesture">}}

{{< /gallery >}}

# Building

In my first round of building, I went more of a choose your own adventure route. The narrator would weave a story based on which constellations you picked and there were different constellations that you could pick at different times in the video.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510674036/Screenshot_2017-11-13_20.14.28_drhynu.png" title="Space snake">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510674036/Screenshot_2017-11-13_20.40.01_dg2zfo.png" title="Guardian cat" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510674036/Screenshot_2017-11-13_20.40.011_kxhkau.png" title="Turbaned woman" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510674036/Screenshot_2017-11-13_20.28.05_ogbvp1.png" title="Peace dove" >}}

{{< /gallery >}}


Since I am not an expert star gazer, many of the constellations in this program are actually fictional. I had trouble myself finding anything that wasn't The Big Dipper and I thought it would add a nice personal touch. 

I made up five different constellations and came up with six different storylines from the different combinations of constellations. There were three hero constellations: an interstellar doomsday serpent, a large protector feline, and a god-like being who could see all of the universe. For enemies, I created a local human woman prone to selfish desires and a peace bringing dove who sometimes messes things up.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850872/New_Doc_2017-12-09_41_smlfp6.jpg" title="Story brainstorming">}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1512850874/New_Doc_2017-12-09_42_tn9abu.jpg" title="Story writing">}}

{{< /gallery >}}

After some feedback, I decided to try to utilize the lower half of the screen more as the user spends most of their time looking up at the sky. Initially I wanted to play another 360 video in the lower half but the technical aspects of it I wasn't able to grasp in time.

Instead, I decided to take advantage of using planes or terrains in Unity to change the scenery. For example, if you were to click on a sand or desert related constellation, the scene would change appropriately.

{{< gallery hover-effect="none" caption-effect="none" >}}

{{<figure src="http://res.cloudinary.com/dvozrk6m8/image/upload/v1510674036/Screenshot_2017-11-13_20.30.05_drgtny.png" title="Scenery changes to rolling sand dunes">}}

{{< /gallery >}}

# Final Notes

I enjoyed working on this project. The bulk of it involved some creative writing and searching for constellations myself. I wish I could have found more constellations or made it less structured however I am pleased with the overall documentary-like atmosphere that it provides. In terms of interaction, it would have been cool to do the glove idea but trying to incorporate terrains and to utilize the lower half of the screen in general took too much time.

# Credits

* [Bensound](https://www.bensound.com/)
* [Ground Materials Sample by Miolaj Spychal](https://www.assetstore.unity3d.com/en/#!/content/55437)
* [Twelve Hours at Grand Staircase-Escalante by William Briscoe Photography](https://www.youtube.com/watch?v=NvTs-FANx1Y)
* [NetworkIt by Kevin Ta](https://github.com/kevinta893/NetworkIt)