---
published: true
layout: post
comments: true
title: Zelda 1 Demake (EECS 494)
unity_dir: eecs_494_p1_zelda
permalink: /projects/Zelda-1-Demake-(EECS-494)
---

Hi there! Today I'll be writing about the first of 3 project blog posts about my work in the University of Michigan's game development course, EECS 494.

- Image Embed
    ![{{ALT TEXT}}](/assets/images/projects/{{REMAINING PATH}}){: width="250" }

- Site Link
    [{{LINK TEXT}}](https://WEBSITE.com/SOMETHING)

- Download Link
    [here](assets/downloads/{{REMAINING PATH}})

- YouTube Embed
    <center> <iframe width="560"
            height="315"
            src="https://youtube.com/embed/1brraN6m7VA"
            frameborder="0"
            allow="autoplay; encrypted-media"
            allowfullscreen></iframe></center>

- Unity WebGL Embed
    {{ADD THE TAG: "unity_dir: {{GAME FOLDER NAME}}"}}

    <script src="/assets/unity/{{page.unity_dir}}/TemplateData/UnityProgress.js"></script>  
    <script src="/assets/unity/{{page.unity_dir}}/Build/UnityLoader.js"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/unity/{{page.unity_dir}}/Build/builds.json",{onProgress: UnityProgress});  
    </script>
    <div class="webgl-content">
      <div id="gameContainer" style="width: 960px; height: 600px"></div>
    </div>

Have fun writing!  
-Robert
