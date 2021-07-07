<template>
  <div>
      <img :src="details.thumb" alt="details.series">
      <p>{{details.series}}</p>
  </div>
</template>
      

<script>
    export default {
    name:"ProductCard",
    props:["details"]
}
</script>

<style lang="scss" scoped>

div{
    width: 200px;
    p{
        color: white;
        font-size: 10px;
        text-transform: uppercase;
    }
}
img{
    width: 200px;
    height: 200px;
}

</style>