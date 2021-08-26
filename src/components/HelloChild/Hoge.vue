<template>
   <div>
      <h2>{{ hoge }}</h2>
      <fuga />
   </div>
</template>

<script>
import Fuga from './progeny/Fuga'
export default {
  components: {
    fuga: Fuga
  },
  inject: ['hoge'],
}
</script>

<style>

</style>