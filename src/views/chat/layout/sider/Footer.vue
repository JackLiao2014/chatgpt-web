<script setup lang='ts'>
import { defineAsyncComponent, ref } from 'vue'

const Setting = defineAsyncComponent(() => import('@/components/common/Setting/index.vue'))

const show = ref(false)
</script>
