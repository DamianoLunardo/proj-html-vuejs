<script>
import AppMainTop from './AppMainTop.vue';
import AppMainCenter1 from './AppMainCenter1.vue';
import AppMainCenter2 from './AppMainCenter2.vue';
import AppMainCenter3 from './AppMainCenter3.vue';
import AppMainCenter4 from './AppMainCenter4.vue';
import AppMainCenter5 from './AppMainCenter5.vue';
import AppMainCenter6 from './AppMainCenter6.vue';
import AppMainCenter7 from './AppMainCenter7.vue';

export default {
  components: {
    AppMainTop,
    AppMainCenter1,
    AppMainCenter2,
    AppMainCenter3,
    AppMainCenter4,
    AppMainCenter5,
    AppMainCenter6,
    AppMainCenter7,
    
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
<AppMainCenter2/>
<AppMainCenter3/>
<AppMainCenter4/>
<AppMainCenter5/>
<AppMainCenter6/>
<AppMainCenter7/>
</template>

<style lang="scss" scoped>

</style>