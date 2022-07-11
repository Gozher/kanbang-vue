

<template>


  <app-header />

  <div class="container mx-auto my-2">
    <router-view></router-view>
  </div>

  <app-footer />

</template>

<script setup>

import AppHeader from '@/components/AppHeader.vue'
import AppFooter from '@/components/AppFooter.vue'

</script>

<style>
</style>
