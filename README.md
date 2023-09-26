# Ronaldo-and-Messi
Ronaldo and Messi are both respected soccer players and are both GOATs of soccer.
<body> 
<img src="https://images.hola.com/us/images/027a-167b21aec371-35f735bf18e8-1000/vertical-1150/cristiano-y-messi.png" />
</body>
<!DOCTYPE html>
<html>
<body>

<h1>The template Element</h1>

<p>Click the button below to display the hidden content from the template element.</p>

<button onclick="showContent()">Show hidden content</button>

<template>
  <h2>Flower</h2>
  <img src="img_white_flower.jpg" width="214" height="204">
</template>

<script>
function showContent() {
  let temp = document.getElementsByTagName("template")[0];
  let clon = temp.content.cloneNode(true);
  document.body.appendChild(clon);
}
</script>

</body>
</html>
