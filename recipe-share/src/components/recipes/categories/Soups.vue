<template>
  <div class="row justify-content-center">
    <div class="card-grid" v-for="(recipe, index) in recipes" :key="index">
      <div class="card" style="width: 18rem;" v-if="recipe.category == 'Супи' ">
        <router-link :to="{ name: 'recipeDetails', params: { recipe, id: recipe.id }}">
          <img :src="recipe.img" class="card-img-top" :alt="recipe.name" />
        </router-link>
        <div class="card-body">
          <router-link :to="{ name: 'recipeDetails', params: { recipe, id: recipe.id }}">
            <h4 class="card-title">{{ recipe.name }}</h4>
          </router-link>
          <router-link :to="{ name: 'recipeDetails', params: { recipe, id: recipe.id }}">
            <a href="#" class="btn btn-secondary">Виж повече</a>
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { db } from "../../../firebase";

export default {
  name: "Soups",
  data: function() {
    return {
      recipes: []
    };
  },
  firestore: {
    recipes: db.collection("Recipes").orderBy("category")
  }
};
</script>

<style scoped>
.card {
  display: inline-block;
  margin: 10px;
  color: black;
}

img {
  cursor: default;
  height: 220px;
  width: 286px;
  border: 5px solid white;
}

.card-body a {
  text-decoration: none;
}

.card-body a h4 {
  cursor: default;
  color: black;
  text-decoration: none;
}
</style>