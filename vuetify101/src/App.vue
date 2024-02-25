<template>
  <v-layout class="rounded rounded-md">
    <v-app-bar title="Application bar"></v-app-bar>

  <v-navigation-drawer>
    <v-list-item title="Cosas que hacer" subtitle="y mas..."></v-list-item>
    <v-divider></v-divider>
    <v-list-item  title="Home" link to="/"></v-list-item>
    <v-list-item  title="Diversion" link to="/diversionP"></v-list-item>
    <v-list-item  title="To-Do" link to="/listaP"></v-list-item>
  </v-navigation-drawer>

    <v-main class="d-flex align-center justify-center" style="min-height: 300px;">
      <router-view/>
    </v-main>
  </v-layout>
</template>

<script setup>
  //
</script>
