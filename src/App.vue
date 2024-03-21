<script>
  export default{
    data(){
      return{
        title: 'Hello word',
        text: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi et suscipit laborum blanditiis tempore vel repellat dolorum, adipisci atque accusamus consectetur quae reprehenderit magni esse! Atque magnam aliquid iste dolore?'
      }
    }
  }
</script>

<template>
  <div class="page">
    <div class="text">
      <h1 class="fw-bold main-title">{{ title }}</h1>
      <p class="text-center fs-3">{{ text }}</p>
    </div>
  </div>
</template>

<style scoped>
h1{
  color: yellow;
}

p{
  color:red;
}
</style>