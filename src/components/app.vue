<template>
<div>
  <p>Hello Jessie</p>

  <VueButton text="Primer boton"></VueButton>
  <VueButton text="Hola"></VueButton>
  <VueButton text="Que tal?"></VueButton>
  <VueButton text="Que onda?"></VueButton>

 <ul>
      <li>Elemento 1</li>
      <li>Elemento 2</li>
  </ul>

</div>
</template>

<script>
import './../css/style.css';
import VueButton from './VueButton.vue';

export default {
    components: {
        VueButton
    }
}
</script>

<style>
    p{
        color: red;;
    }
</style>