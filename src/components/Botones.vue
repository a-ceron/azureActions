<template>
    <div class="botones">
    <!-- PAra mutations usamos commits -->
    <!-- PAra actions usamos dispatch -->
    <button @click="$store.dispatch('bajarContador')">-</button>
    <button @click="$store.dispatch('subirContador')">+</button>
  </div>
</template>

<script>
export default {
    name: 'Botones',
}
</script>
