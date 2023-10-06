<template>
<div>
 <Qwe />
  <router-view/>
 <Dsa />
</div>

</template>

<script>

import Dsa from './components/Dsa.vue'
import Qwe from './components/Qwe.vue'


export default {
  components: {

    Dsa,
    Qwe,

}
}
</script>

<style>

</style>
