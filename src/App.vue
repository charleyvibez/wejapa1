<template>
  <div id="app">
    <myname :name="name"></myname>
  </div>
</template>

<script>
import Name from './components/MyName'
export default {
  name: 'app',
  data() {
    return {
      name: 'Williams Charles'
    }
  },
  components: {
    myname: Name
  }
}
</script>