<template>
  <SmartGangApp/>
</template>
<script>
import SmartGangApp from "./components/SmartGangApp";
import('./app.scss')
import('./assets/styles/_font.scss')
import('./assets/styles/_mixin.scss')
import('./assets/styles/_variables.scss')

export default {
  name: 'App',

  components: {
    SmartGangApp

  },

  data: () => ({
    //
  }),
}
</script>
