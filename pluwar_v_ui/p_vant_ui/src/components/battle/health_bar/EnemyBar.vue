<script setup>
    import healthinfo from '@/components/battle/health_bar/HealthInfo.vue'
</script>
<template>
    <!--先烂着-->
    <healthinfo :health="enemyHealth" :maxhealth="enemyMaxHealth" :name="enemyName" :color="enemyColor" />
</template>
