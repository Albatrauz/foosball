<script lang="ts">
const user = useSupabaseUser()
</script>
<template>
    <div>
        Welcome {{ user.email }}
    </div>
</template>

<style scoped>

</style>