<template>
<div class="recipes">
  <h1>Flan Recipe</h1>
  <img alt="flan" src="flan.jpg" width=250px>
  <div class="ingredients">
    <h2>Ingredients</h2>
    <hr>
    <div class="list">
      <ul>
        <input type="checkbox">
        <label> 1 Cup white sugar</label><br>
        <input type="checkbox">
        <label> 1 Cup white sugar</label><br>
        <input type="checkbox">
        <label> 3 Eggs </label><br>
        <input type="checkbox">
        <label> 1 can condensed milk </label><br>
        <input type="checkbox">
        <label> 1 can evaporated milk </label><br>
        <input type="checkbox">
        <label> 1 tbsp vanilla extract</label><br>
      </ul>
    </div>
  </div>
  <div class="instructions">
    <h2>Instructions</h2>
    <hr>
    <h4>
      <ol>
        <li> Preheat oven to 350 degrees F</li>
        <li> In a medium saucepan over medium-low heat, melt sugar until golden in color.
          Carefully pour hot syrup into a 9 inch round glass baking dish, turning the dish
          to evenly coat the bottom and sides. Set aside.</li>
        <li> In a large bowl, beat eggs. Beat in condensed milk, evaporated milk and vanilla
          until smooth. Pour egg mixture into baking dish. Cover with aluminum foil.</li>
        <li> Bake in preheated oven 60 minutes. Let cool completely</li>
        <li> To serve, carefully invert on serving plate with edges when completely cool.</li>
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
