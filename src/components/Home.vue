<template>
    <div>
        <h1>Home</h1>
        <button @click="goto" class="btn btn-success">Let's go !</button>
    </div>
</template>

<script>
export default{
    methods:{
        goto(){
            this.$router.go(-1)
        }
    }
}
</script>
