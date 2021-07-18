<template>
  <div id="app">
    <h3>
    <img src="./assets/kitfavela.png" class="logo">
    <kitquebrada msg="Welcome to Your Ixepa.js App"/>
    <h5>
    <p>Mais de 116 milhões de brasileiros não têm comida suficiente ou passam fome, diz pesquisa.</p>
    </h5>
      </h3>
      <ul type="disc"> 
    <li id="menu1" class="menu-title"> <a href="https://instagram.com/kitquebradaoficial?utm_medium=copy_link" target="_blank"> Conheça&nbsp;a Kit Quebrada </a> </li>
    <li> <a href="https://mail.google.com/mail/u/0/#inbox?compose=new" target="_blank">Trabalhe Conosco</a> </li>
    <li>Doe uma Cesta</li>
    <li> <a href="https://drive.google.com/file/d/12EPtqFffRas6-02NOXz9NLCWU1hKRsPX/view?usp=drivesdk" target="_blank">Seja um doador</a> </li>
    <li><a href="#test">suporte</a></li>
  </ul> 
  </div>

</template>

<script>
import kitquebrada from './components/kitquebrada.vue'

export default {
  name: 'App',
  components: {
    kitquebrada
  }
}
</script>

<style>
.logo{
  width: 300px;
  height: 300px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
