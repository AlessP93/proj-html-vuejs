<template>
  <main>
    <sectionOne/>
    <sectionTwo/>
    <sectionThree/>
 
  </main>
</template>

<script>
import sectionOne from '../sections/sectionOne.vue'
import sectionTwo from '../sections/sectionTwo.vue'
import sectionThree from '../sections/sectionThree.vue'

export default {
    name:'BaseMain',
    components: {
        sectionOne,
        sectionTwo,
        sectionThree,
    },
}
</script>

<style lang="scss" scoped>

</style>