<template lang="pug">
- pageTitle = "Awesome Boilerplate"
v-app
   v-app-bar(app)
      v-toolbar-title.headline.text-uppercase= pageTitle
      v-spacer
   v-content
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>
