<template>
  <header>

  <nav class='container'>

<nav>
      <h1><a href="/">MEUTIME</a></h1>
    <div id="menu-items">
      <ul>
        <li><a href="/">Partidas</a></li>
        <li><a href="/meus_times">Meus times</a></li>
        <li><a href="/comunidade">Comunidade</a></li>
        <li><a href="/ovidades">Novidades</a></li>
      </ul>
    </div>
    <div id="user">
      <li><a href="/ovidades">Usuário</a></li>
    </div>
</nav>
  </header>

  <body>

    <div id="imagem">
    </div>
  </body>
</template>

<script>
export default {
  name: 'Header',
}

</script>
<style scoped>

header {
  background-color: var(--color-background-nav);
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
}
nav{
  display: flex;
  align-items: center;
}
h1 {
  font-size: 27px;
  background: -webkit-linear-gradient(right, #F5760F 53%, #ffffff 0%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  
}
#menu-items{
  position: fixed;
  top:center;
  left:25%;
}
ul{
  list-style: none;
  text-transform: uppercase;
  font-family: arial;
  font-size: 14px;
}
ul li{
  display:inline;
  padding-right: 90px;
}
ul li a{
  color: var(--color-background-meu);
}
a:hover {
  color: #F5760F;
}
 #user{
  position: fixed;
  top:center;
  left:90%;
}

 #user li{
   list-style: none;
   text-transform: uppercase;
   font-size: 14px;
 }
 #user a{
   color: var(--color-background-meu);
 }

 #user a:hover {
  color: #F5760F;
}
#imagem {
   background-image: url("https://drive.google.com/file/d/17mzH-Jg1tngKuykqqUDvoKm2QI_3664Q/view?usp=share_link");
   height: 400px;
   width: 100%;
}
</style>