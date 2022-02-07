<template>
    <ul>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
      <li><button class="btn-hist"><img src="http://localhost:8000/imgs/LMgG8oT__400x400.jpg" width="50px" alt=""></button></li>
    
    </ul>
</template>

<script>
export default {
  name: "Histories",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
  /* box-sizing: border-box; */
}
ul {
  margin-top: 10px;
  margin-bottom: 10px;
  list-style: none;
  border: 0.5px solid rgba(0,0,0,0.3);
  border-radius: 3px;
  padding: 15px;
   
}
ul li {
  
  display: inline;
  margin: 10px;
}
.btn-hist{
  background: none;
  border: none;
}
.btn-hist img{
  border-radius: 100%;
}


</style>
