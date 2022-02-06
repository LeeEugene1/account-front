<template>
    <div>
        <Nuxt/>
    </div>
</template>
<script>
export default {
    created(){
        // localStorage check
        if(process.browser){
            const token = localStorage.getItem('token')
            console.log(token)
        }
    },
}
</script>
<style lang="">
    
</style>