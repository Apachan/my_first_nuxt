<template>
  <section>
    <sample-component>
      Hello Slot!
      <div slot="named">
        named slot
      </div>
    </sample-component>
    <nuxt-link to="/about">ABOUT</nuxt-link>
  </section>
</template>
​
<script>
import SampleComponent from '~/components/SampleComponent.vue'
export default {
  components: {
    SampleComponent
  }
}
</script>

