<template>
  <v-app>
    <Toolbar />
    <Footer />
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Toolbar from './components/Toolbar'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Toolbar,
    Footer
  },
  data () {
    return {
      //
    }
  }
}
</script>
