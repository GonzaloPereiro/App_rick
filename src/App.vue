<template>
  <div>
    <h1>Rick And Morty</h1>
    <FilterByStatus />
    <ListCharacters />
  </div>
</template>

<script>
import ListCharacters from '@/components/ListCharacters'
import FilterByStatus from '@/components/FilterByStatus'
export default {
  name: 'App',
  components: {
     ListCharacters,
     FilterByStatus,
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  background-color: #24282f;
  color: white;
}

h1{
  font-size: 3rem;
  margin-bottom: 2rem;
  text-align: center;
}

.container{
  width: 980px;
  max-width: 90%;
  margin: 5rem auto;
}
img{
  width: 100%;
} 

</style>
