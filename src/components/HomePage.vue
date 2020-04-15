<template>
<div class="hello">
  <div class="title">
    <h1>Welcome</h1>
  </div>
  <h3>New recipes every Friday at noon!</h3>
  <br><br>
  <div class="row">
    <div class="col">
      <div class="row">
        <img alt="flan" src="flan.jpg" width=250px>
      </div>
      <div class="row">
        <router-link to="/flan">Flan</router-link>
      </div>
      <div class="row">
        <h4> Flan is one of South America's most loved
          desserts. Try this recipe, we are sure you will
          fall in love with it like we did!</h4>
      </div>
    </div>
    <div class="col">
      <div class="row">
        <img alt="crepes" src="crepe.jpg">
      </div>
      <div class="row">
        <router-link to="/crepes">Strawberry Crepes</router-link>
      </div>
      <div class="row">
        <h4> Crepes are by far our favorite breakfast, lunch, and
          dinner. They are not the healthiest but they are the yummiest!</h4>
      </div>
    </div>
  </div>
  <footer>
    <p>
      <center><a class="a-github" href="https://github.com/pfiguer2/CP3">
          GitHub Link</a></center>
    </p>
  </footer>
</div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  font-family: 'Courgette', cursive;
}

.row {
  justify-content: space-around;
}

.col {
  border-style: solid;
  margin: 20px 150px 20px 150px;
}

.title {
  background: #d96a57;
  border: 10 0 10 0px;
}

img {
  padding: 10px;
  padding-top: 20px;
}

h1 {
  color: white;
}

ul {
  list-style-type: none;
  padding: 0;
}

h4 {
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 20px;
}

a {
  color: #d96a57;
  font-size: 35px;
  text-decoration: none;
}

.a-github {
  color: #d96a57;
  font-size: 15px;
  text-decoration: none;
}
</style>
