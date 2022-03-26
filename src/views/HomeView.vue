<template>
  <div>
      <h1>This is Home page</h1>
      <JieunView />
  </div>
</template>

<script>
import JieunView from '@/components/JieunView.vue'
export default {
  components: { 
    JieunView 
  },
  data(){
    return {
      name: 'Jieun'
    }
  }
}
</script>

<style scoped>
  h1 {
    font-size: red;
  }
</style>