---
published: true
layout: post
comments: true
title: Toaster Story (EECS 494)
unity_dir: Toaster_Story_Web_Build
permalink: /projects/Toaster_Story
---

Hi there! Welcome to blog 2 of 3 about my work in the University of Michigan's game development course, EECS 494! After remaking the first dungeon of Zelda 1 with a partner last time, for this project we were let loose to build out our own cool ideas. I went for the exciting combination of a top-down shooting deckbuilder, and this blog will be a bit about the process to get there. If you're curious how a Toaster's Story plays into all of this, keep reading below!  

If you're reading this, you're a bit early! I haven't quite found the time to write up a blogpost here between project deadlines and midterms, so check back a bit later if you're interested. That being said, I don't want to keep you from trying out game. Check out the download links for Windows and Mac below, or just playing in your browser further below, although you will be much better performance out of the Windows and Mac builds.  

[Download the Windows build here](/assets/downloads/projects/Toaster_Story/Toaster_Story_Windows.zip).  

[Download the Mac build here](/assets/downloads/projects/Toaster_Story/Toaster_Story_Mac.zip).   

<center><script src="/assets/unity/{{page.unity_dir}}/TemplateData/UnityProgress.js"></script>  
<script src="/assets/unity/{{page.unity_dir}}/Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/unity/{{page.unity_dir}}/Build/{{page.unity_dir}}.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 785px; height: 589px"></div>
</div></center>  

Have fun,  
-Robert
