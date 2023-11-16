<script>
import AppMainTop from './AppMainTop.vue';
import AppMainCenter1 from './AppMainCenter1.vue';
import AppMainCenter2 from './AppMainCenter2.vue';

export default {
  components: {
    AppMainTop,
    AppMainCenter1,
    AppMainCenter2,
    
  },
  data () {
    return {
      message: 'Ciao',
    
    }
  }
}
</script>

<template>
<AppMainTop/>
<AppMainCenter1/>
<AppMainCenter2 />
</template>

<style lang="scss" scoped>

</style>