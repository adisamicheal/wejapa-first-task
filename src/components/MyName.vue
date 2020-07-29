<template>
  <div>
     <p>Hi there 👋 </p>
     <p>I am {{ name }} </p>
  </div>
</template>

<script>
export default {
    props: {
    name : {
      type: String
    }
  }
}
</script>

<style scoped>
p {
  font-weight: 600;
  font-size: 36px;
}
</style>