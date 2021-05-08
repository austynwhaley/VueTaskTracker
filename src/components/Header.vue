<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
    import AddBtn from './AddBtn'
    export default {
        name: 'Header',
        props: {
            title: String
        },
        components:{
            AddBtn
        }
    }
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
