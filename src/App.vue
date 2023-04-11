<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  components: {
    MyHeader,
    MyFooter


  },
  data() {
    return {

    }

  },
  methods: {

  }

}

</script>

<template>
  <MyHeader></MyHeader>
  <main>

  </main>

  <MyFooter></MyFooter>
</template>

<style scoped lang="scss">
@use './styles/general.scss'
</style>
