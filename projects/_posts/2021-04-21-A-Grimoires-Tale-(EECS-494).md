---
published: true
layout: post
comments: true
title: A Grimoire's Tale (EECS 494)
unity_dir: A Grimoire's Tale - Web Build
permalink: /projects/A_Grimoires_Tale
---

Hi there! Welcome to blog 3 of 3 about my work in the University of Michigan's game development course, EECS 494! If you're seeing this, you're here early! I've got the game for you to checkout here now, but come back later for a full write-up about the development process the game.

If you're just looking to play the game, look no further! Check it out itch.io for a download link, check out our game trailer, or just play on site here.

[Check out the game here!](https://toastylionstudios.itch.io/a-grimoires-tale)  

[Watch the game's trailer here.](https://www.youtube.com/watch?v=1fcMwpITjCY)  

<center><script src="/assets/unity/{{page.unity_dir}}/TemplateData/UnityProgress.js"></script>  
<script src="/assets/unity/{{page.unity_dir}}/Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/unity/{{page.unity_dir}}/Build/{{page.unity_dir}}.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 720px; height: 405px"></div>
</div></center>  

See you soon,  
-Robert
