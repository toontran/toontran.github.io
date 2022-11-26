---
permalink: /philosophy/
title: "A bit about My Philosophy"
author_profile: true
redirect_from: 
  - /philo/
  - /philosophy.html
---

To be updated.

<!-- 
Consciousness ->
CS ->
Epistemology ->
Math ->
What do we know, how do we know: math & logic (may actually be one)
inductive bias
 -->
<html>
  <body>
    Here is one mermaid diagram:
    <div class="mermaid" id="brug">
      graph TD 
      A-->B
      B-->C(ukgukgk gkgkjkj gkjkjgkh asd fasdf adsf adsf asf)
      click C "http://www.github.com" "This is a tooltip for a link" 
    </div>
    <div class="mermaid">
      graph TD 
      A-->B
      B-->C(ukgukgk gkgkjkj gkjkjgkh asd fasdf adsf adsf asf)
      click C callback "This is a tooltip for a link" 
    </div>
    <script>
      var callback = function(){
        alert('A callback was triggered');
      }
    </script>
    <script type="module">
      import mermaid from 'https://unpkg.com/mermaid@9.1.3/dist/mermaid.esm.min.mjs';
      mermaid.initialize({ startOnLoad: true });
    </script>
  </body>
</html>

<!-- gantt
      title A Gantt Diagram
      dateFormat  YYYY-MM-DD
      section Section
      A task           :a1, 2014-01-01, 30d
      Another task     :after a1  , 20d
      section Another
      Task in sec      :2014-01-12  , 12d
      another task      : 24d -->