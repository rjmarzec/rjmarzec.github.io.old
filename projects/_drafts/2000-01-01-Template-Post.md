---
published: false
layout: post
comments: true
title: Template Post
permalink: /projects/[TITLE]
---

This is a template post. Use this as a starting point for other posts.

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
    {{ALSO, MODIFY "{{BUILD NAME}}" DOWN BELOW}}

    <script src="/assets/unity/{{page.unity_dir}}/TemplateData/UnityProgress.js"></script>  
    <script src="/assets/unity/{{page.unity_dir}}/Build/UnityLoader.js"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/unity/{{page.unity_dir}}/Build/{{BUILD NAME}}.json",{onProgress: UnityProgress});  
    </script>
    <div class="webgl-content">
      <div id="gameContainer" style="width: 960px; height: 600px"></div>
    </div>

Have fun writing!  
-Robert
