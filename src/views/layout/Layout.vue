<template>
    <div class="flex justify-between space-x-4 ">
        <left-side class="flex-none w-1/6 min-h-screen bg-red-400" />
        <content class="flex-1 min-h-screen" />
        <right-sider class="flex-none w-1/6 min-h-screen bg-yellow-200" />
    </div>
</template>

<script lang="ts">
import Content from './Content.vue';
import LeftSide from './LeftSide.vue';
import RightSider from './RightSider.vue';
export default {
    components: { Content, LeftSide, RightSider }
}
</script>

<style scoped>
</style>
