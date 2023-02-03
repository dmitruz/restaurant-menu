<template>
  <div class="bg-gray-100 h-full">
    <header class="bg-white shadow h-16 flex justify-between items-center">
      <router-link :to="{ name: 'home' }" class="inline-flex items-center h-full px-5"> Home </router-link>
      <div class="flex items-center gap-1>
        <router-link to="/" class="inline-flex items-center px-2 h-full hover:bg-purple-200"
          >Search Meal</router-link
        >
        <router-link to="/" class="inline-flex items-center px-2 h-full hover:bg-purple-200"
          >Meals by Letter</router-link
        >
        <router-link to="/" class="inline-flex items-center  px-2 h-full hover:bg-purple-200"
          >Meals by Ingredient</router-link
        >
      </div>
    </header>
  </div>
  <router-view />
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
