<!DOCTYPE html>
<html>
<head>
  <title>Concatenation Example</title>
</head>
<body>

  <h2>My Fun Sentence Using Concatenation</h2>

  <!-- This paragraph will display the result -->
  <p id="output"></p>

  <script>
    // Variables with parts of the sentence
    var phraseStart = "How much I love to combine ";
    var food = "HotDog";
    var extra = "Jelly";

    // Concatenate the parts together
    var fullSentence = phraseStart + food + extra;

    // Show the sentence on the page
    document.getElementById("output").textContent = fullSentence;
  </script>

</body>
</html>

