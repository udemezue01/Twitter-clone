<template>
  <div class="container mx-auto px-4 grid grid-cols-3">
    <div>
      <sectionone/>
    </div>
    <div>
     <sectiontwo/>
    </div>
    <div>
      <sectionthree/>
    </div>
  </div>
</template>

<script>
import Sectionone from '~/components/Sectionone.vue'
import Sectiontwo from '~/components/Sectiontwo.vue'
export default {
  components: { Sectionone, Sectiontwo },
  name: 'IndexPage'
}
</script>
