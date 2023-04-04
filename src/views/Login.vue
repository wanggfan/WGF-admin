<template>
   <div>

      <el-button type='success'>11</el-button>

      <button class="tn" @click="tzzy">
         2222
      </button>
    
   </div>
</template>
<script setup>
import { useRoute, useRouter } from 'vue-router';
import { ref, reactive, onMounted, } from 'vue';
const router = useRouter();
const tzzy = () => {
   router.push("/");
   console.log(111);

}


</script>
<style lang='scss' scoped>
// .tn {
//    @apply bg-pink-600 py-96 px-44 rounded-2xl animate-none hover: bg-red-900 duration-1000
// }
</style>
