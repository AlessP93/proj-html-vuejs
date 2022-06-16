<template>
  <main>
    <sectionOne/>
    <sectionTwo/>
    <sectionThree/>
    <sectionFour/>
    <sectionFive/>,
  </main>
</template>

<script>
import sectionOne from '../sections/sectionOne.vue'
import sectionTwo from '../sections/sectionTwo.vue'
import sectionThree from '../sections/sectionThree.vue'
import sectionFour from '../sections/sectionFour.vue'
import sectionFive from '../sections/sectionFive.vue'

export default {
    name:'BaseMain',
    components: {
        sectionOne,
        sectionTwo,
        sectionThree,
        sectionFour,
        sectionFive,
    },
}
</script>

<style lang="scss" scoped>

</style>