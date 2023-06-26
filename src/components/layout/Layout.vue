<template>
    <div class="layout">
        <VHeader></VHeader>
        <div class="content">
            <Sidebar></Sidebar>
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
import Sidebar from './Sidebar';
import VHeader from './VHeader';
export default {
    components: {
        Sidebar,
        VHeader
    }
}
</script>
<style lang="less" >
.layout {
    display: flex;
    flex-direction: column;  
    .content {
       flex: 1;
        display: flex;
       
    }
}
</style>