<template>
  <header>
    <Nav/>
  </header>
  <main>
    <section>
      <Histories/>
    </section>
    <div v-for="post in 'string'" :key="post">
      <Post />
    </div>
  </main>
</template>

<script>
import Nav from './components/Nav.vue'
import Histories from './components/Histories.vue'
import Post from './components/Post.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Histories,
    Post
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: rgba(var(--b3f,250,250,250),1);
}
main{
  margin-top:10px;
  width: 95%;
  /* border: 1px solid gray; */
  position: relative;
  top: 10px;
  margin: 0 auto;
  height: 100vh;
}
</style>
