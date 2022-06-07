<!-- <script>
import TopImage from '@/components/TopImage.vue'
export default {
  components: {
    TopImage
  }
}
</script> -->

<script setup>
import TopImage from '@/components/TopImage.vue'
import LeftMenu from '@/components/LeftMenu.vue'
import LeftUpdate from '@/components/LeftUpdate.vue'
import RightMarquee from '@/components/RightMarquee.vue'
import RightMain from '@/components/RightMain.vue'
import FooterText from '@/components/FooterText.vue'
</script>

<template lang="pug">
TopImage
#center
  #left
    LeftMenu
    LeftUpdate
  #right
    RightMarquee
    RightMain
FooterText
</template>


