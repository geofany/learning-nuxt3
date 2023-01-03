<template>
  <div>
    <h1>
      About
    </h1>

    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel totam dicta, sint accusantium fugit at odit eaque
      nulla, laudantium magnam enim necessitatibus possimus quidem repellat. Odio doloremque unde necessitatibus ad?
    </p>

    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel totam dicta, sint accusantium fugit at odit eaque
      nulla, laudantium magnam enim necessitatibus possimus quidem repellat. Odio doloremque unde necessitatibus ad?
    </p>
    <div>
      {{ data }}
    </div>
  </div>
</template>
  
<script setup>
  // const { data } = await useFetch('/api/ninja?name=mario', {
  //   method: 'post',
  //   body: { age: 30 }
  // })

  const { data } = await useFetch('/api/currency/GBP')
</script>
  
<style>

</style>