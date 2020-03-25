<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="shadow-2">
      <q-toolbar style="background: #fff">
        <q-toolbar-title class="text-weight-bolder" style="color: #a67f78">
          <!-- poolda -->
          poolda
        </q-toolbar-title>
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'MainLayout',
  data () {
    return {
    }
  }
}
</script>
