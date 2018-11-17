<template lang="html">
  <nuxt-link to="/">TOP</nuxt-link>
</template>
​
<script>
export default {}
</script>
​
<style lang="scss">
</style>

<script>
export default {
  head () {
    return {
      // タイトルテンプレートがある場合は "ABOUT - ポートフォリオ" になる
      title: 'ABOUT',
      meta: [
        { hid: 'description', name: 'description', content: 'About ページ' }
      ]
    }
  }
}
</script>

<script>
export default {
  layout: 'dark'
}
</script>