<template>
  <div class="container">
    <Search />
    <MyList />
  </div>
</template>

<script>
import Search from './components/Search.vue'
import MyList from './components/MyList.vue'

export default {
  name: 'App',
  components: {
    Search,MyList
  }
}
</script>

<style>

</style>
