<script setup>
// aqui teremos a lógica
// função, imports, variaveis

import coracao from "./assets/coracao.png"
import curtido from "./assets/curtido.png"


</script>

<template>
  <!-- tags, ou seja tudo q sera renderizado na tela -->
 <header>
 <h1>VueLab</h1>
 <input type="text">
 </header>

 <main>

  <section>
    <div>
      <p>17 de ago, 2024</p>
      <!-- diretivas -->
      <!-- para renderizar um dado q ta na logica, se for uma tag usaremos {{  }} -->
       <!-- para renderizar em atributos (src, href e etc) usaremos o v-bind, que é os : é o atalho do v-bind -->
      <img :src="curtido" alt="">
      <h3> O que é linguagem de programação? Conheça as principais</h3>
      <p>Uma das mais populares vertentes da tecnologia da informação, a área de programação segue tendo muita demanda de trabalho justamente pela velocidade com que dispositivos tecnológicos vêm avançando.</p>
    </div>
  </section>

  <section>
    <div>
      <p>12 de jul, 2024</p>
      <img :src="coracao" alt="">
      <h3> GitHub agora permite fazer login sem precisar de senha</h3>
      <p>O GitHub anunciou nesta quarta-feira (12) o acesso a partir das passkeys, método de autenticação sem senhas. A novidade está disponível em uma versão beta pública e pode substituir a autenticação em dois fatores.</p>
    </div>
  </section>

  <section>
    <div>
      <p>21 de jun, 2024</p>
    
      <img :src="coracao" alt="">
      <h3> Por que os hiperlinks são azuis em sua maioria?</h3>
      <p>Quem navega na internet, certamente já percebeu que ela conta com diversos recursos para tornar a nossa vida mais fácil. Entre essas opções podemos mencionar os hiperlinks – uma palavra ou termo clicável que direciona o leitor.</p>
    </div>
  </section>

 </main>
</template>

<style scoped lang="scss">
/* todo estilo */
header{
  background-color: #17171A;
  h1{
    color: white;
  }
}
main{ 
  background-color: silver;
 
}

</style>
