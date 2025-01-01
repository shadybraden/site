+++  
title = 'Challenges'  
date = 2024-12-30T14:51:02-05:00  
draft = false
+++

## Challenges

JavaScript button here

```
<button id="randomChallengeButton" class="custom-button">Random Challenge (click to earn coins!)</button><br>

  <script>
    document.getElementById("randomChallengeButton").addEventListener("click", function() {
      // Generate a random number between 1 and 100
      const randomNumber = Math.floor(Math.random() * 95) + 1; //edit the "2)" to set the max value based on the total number of challenges

      // Build the file name based on the random number
      const randomChallengeFile = "challenges/" + randomNumber + ".html";

      // Open the random challenge file
      window.location.href = randomChallengeFile;
    });
  </script>
```