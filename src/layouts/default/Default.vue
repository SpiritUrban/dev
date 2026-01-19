<template>
  <v-app>
    <!-- <default-bar /> -->

    <default-view />
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>

<script setup>
  import DefaultView from './View.vue'
</script>
