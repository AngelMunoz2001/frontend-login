 <template>
    <div class="tabla">
        <principal />
    </div>
</template>

<style>
    .tabla{
        padding: 300px;
        
    }
</style>

 <script>
    import principal from '~/components/dashboard/principal.vue';

    export default{
        auth: true,
        layout: 'dashboard',
        components: {
            principal
        }
    }
</script>