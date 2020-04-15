<template>
<div class="recipes">
  <h1>Crepes Recipe</h1>
  <img alt="crepe" src="crepe.jpg" width=250px>
  <div class="ingredients">
    <h2>Ingredients</h2>
    <hr>
    <div class="list">
      <ul>
        <input type="checkbox">
        <label> 2 large eggs</label><br>
        <input type="checkbox">
        <label> 3/4 cup milk</label><br>
        <input type="checkbox">
        <label> 1/2 cup water</label><br>
        <input type="checkbox">
        <label> 1 cup flour </label><br>
        <input type="checkbox">
        <label> 3 tablespoons melted butter </label><br>
        <input type="checkbox">
        <label> Butter, for coating the pan</label><br>
      </ul>
    </div>
  </div>
  <div class="instructions">
    <h2>Instructions</h2>
    <hr>
    <h4>
      <ol>
        <li> In a blender, combine all of the ingredients
          and pulse for 10 seconds. Place the crepe batter in
          the refrigerator for 1 hour. This allows the bubbles
          to subside so the crepes will be less likely to tear
          during cooking. The batter will keep for up to 48 hours.</li>
        <li> Heat a small non-stick pan. Add butter to coat.
          Pour 1 ounce of batter into the center of the pan and
          swirl to spread evenly. Cook for 30 seconds and flip.
          Cook for another 10 seconds and remove to the cutting board.
          Lay them out flat so they can cool. Continue until all batter
          is gone. After they have cooled you can stack them and
          store in sealable plastic bags in the refrigerator for
          several days or in the freezer for up to two months.
          When using frozen crepes, thaw on a rack before gently
          peeling apart.</li>
      </ol>
    </h4>
  </div>
  <footer>
    <p>
      <center><a class="a-github" href="https://github.com/pfiguer2/CP3">
          GitHub Link</a></center>
    </p>
  </footer>
</div>
</template>

<style scoped>
h2 {
  margin: 40px 0 0;
  font-family: 'Courgette', cursive;
}

h4,
.list {
  font-size: 20px;
}

h1 {
  color: #d96a57;
}

ul {
  list-style-type: none;
  padding: 0px;

  display: block;
  list-style-type: decimal;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  padding-inline-start: 40px;
}

.list {
  display: flex;
  justify-content: center;
}

li {
  padding: 5px;
  text-align: left;
}

a {
  color: #d96a57;
  font-size: 25px;
}

.a-github {
  color: #d96a57;
  font-size: 15px;
  text-decoration: none;
}
</style>
