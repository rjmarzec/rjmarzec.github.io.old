---
published: true
layout: post
comments: true
title: Zelda 1 Demake (EECS 494)
unity_dir: eecs_494_p1_zelda
permalink: /projects/Zelda-1-Demake-(EECS-494)
---

Hi there! Today I'll be writing the first of 3 project blog posts about my work in the University of Michigan's Unity game development course, EECS 494! In this first project we were paired up to remake our choice of the first dungeon of the original The Legend of Zelda or some of the original Metroid. As per the title of this post, me and my partner went for remaking Zelda, so he's a bit about that process, including a version of the game you can play in the blogpost. Keep reading for more! *[LOUD AUDIO WARNING]*  

I'll just cut to the chase and leave the web build of the game below! Excuse the loud audio...  

Instructions:  
- Movement: Arrow Keys\  
- Sword attack: X  
- Special Weapons: Z  
- Rotate Special Weapon: Space  
- Custom Ice Wand: C  
- God Mode: 1  
- Custom Level Warp: 4  

<center><script src="/assets/unity/{{page.unity_dir}}/TemplateData/UnityProgress.js"></script>  
<script src="/assets/unity/{{page.unity_dir}}/Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/unity/{{page.unity_dir}}/Build/{{page.unity_dir}}.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 512px; height: 480px"></div>
</div></center>  

As I mentioned at the start, given that this was a group project, what was I responsible for here? Well, we started off with being given most of the sprites necessary and the layout of the dungeon fully completed, but outside of that pretty much everything was built from scratch. My partner and I went about the work by splitting down the middle, each taking roughly half of the tasks we had to get through for the completed product. To get specific, here's what I handled:  

- Grid-based Movement
- Health and damage framework
- Knockback system
- Locked doors
- Item drops on room clear  

And the largest chunk of work was getting every enemy working, including:
- Keese (bats)
- Stalfos (skeletons)
- Goryas (boomerang dudes)
- Gels (slimes)
- Spike traps (spikey boys)
- Wallmasters (creepy hands)
- Aquamentus (final dragon boss)  

For it being such a small project while both me and my partner with still both learning Unity, a lot of it all was just duct-taped together since we didn't know better nor did we need to, but it was still a fun challenge along the way trying to pick up on how to get every piece working properly.  

Also having to collaborate on a larger project like this one was interesting as well. Most of my past projects have just been on my own so I knew how everything operated and what was blocking what from working, but working with a partner to split tasks, learning how to effectively communicate ideas, and learning the Unity Collaborate's watered-down version of source control were all a good part of the learning process of becoming a better developer which was also enjoyable.  

However, the assignment didn't just end there! We also had to put together our own custom level and mechanic in the game. After some thinking we settled on an ice theme, combining the new mechanics of ice tiles that make you slide with no control and an ice wand that lets you freeze enemies. Playing around with the base game to try and add some levels with a unique twist was a lot of fun here! The combination getting locked into sliding and having enemies to freeze that you need to figure out how to move around and slide off of was a really fun experience since it meant we got to break from the chains that was the original level and its exact layout. Anyways, to put it into writing, that meant I also worked on:  

- Ice tiles you slide off of  
- Designing a bunch of puzzle rooms  
- Touching up room aesthetics with different tiles  

If a ice sounds nice to you, go ahead and hit the number 4 on your keyboard to get taken to that secret level and go have fun and let me know what you think in the comments down below.

### Links (but not the one from Zelda)

Although this is where I would normally link a GitHub repo or something, since this is school work that will be assigned against next semester, I don't want to leave it open for plagiarism, so I can't exactly show it here. Sorry.  

However, if the web build isn't enough for you, you can go ahead and download the game as an executable here:  

![Download the Windows build here.](/assets/downloads/projects/EECS_494_Zelda_1_Demake/...)
![Download the Mac Build here.](/assets/downloads/projects/EECS_494_Zelda_1_Demake/...)

Thanks for reading, and I hope you had a fun time playing!
-Robert
