<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br />
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
        >vue-cli documentation</a>.
    </p>
    <h3>Andriely oliveira</h3>
    <RedButton text="Entrar"/>
    <RedButton text="Sair"/>
    <RedButton text="Cadastrar"/>

      
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import RedButton from "@/components/RedButton.vue"

export default defineComponent({
    name: "HelloWorld",
    props: {
        msg: String,
    },
    components: {
      RedButton
    }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h3 {
  margin: 20px 0 0;
}

a {
  color: #42b983;
}
</style>
