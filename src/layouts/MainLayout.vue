
<template>
    <div class="container">
        <div class="auxbar">
            <AuxBar />
            <slot name="auxbar"></slot>
        </div>
        <div class="menu">
            <MenuSidebar />
            <slot name="menu"></slot>
        </div>
        <div class="main-content">
            <slot name="main-content"></slot>
        </div>
    </div>
</template>


<script lang="ts" setup>

import MenuSidebar from '@/components/MenuSidebar.vue';
import AuxBar from '@/components/AuxBar.vue';

</script>