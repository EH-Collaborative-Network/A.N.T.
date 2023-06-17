---
layout: archive
title: Archive
permalink: /archive/
---


This is the archive
<!DOCTYPE html>
<html>
<head>
  <title>Ant Cursor</title>
  <style>
    /* CSS styles for the ant element */
    #ant {
      position: absolute;
      font-size: 24px;
    }
  </style>
</head>
<body>
  <div id="ant">🐜</div>

  <script>
    // JavaScript code to make the ant follow the cursor
    document.addEventListener('mousemove', function(event) {
      var ant = document.getElementById('ant');
      ant.style.left = event.clientX + 'px';
      ant.style.top = event.clientY + 'px';
    });
  </script>
</body>
</html>
