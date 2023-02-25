<template>
    <div style="padding: 20px;">
        <principal />
    </div>
 </template>

 <script>
import principal from '~/components/dashboard/principal.vue';

    export default{
        auth: false,
        layout: 'dashboard',
        components: {
            principal
        }
    }
</script>