<!--HTML BRUTO-->
<template>
    <div>
        <button>{{ text }}</button>
    </div>
</template>

<!--Logica/ Typescript-->
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({

    name: 'RedButton',
    props: {
        text: String,
    },
});

</script>

<!--Estilo-->
<style>
button{
    background-color: rgb(146, 23, 23);
    color: white;
    border: 1px solid black;
    width: 150px;
    padding: 10px 10px;
    font-size: 20px;
    font-weight: bold;
    margin: 20px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover{
    background-color: rgb(229, 30, 30);
}
</style>