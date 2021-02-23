<template>
    <footer>
        <p>{{ footerText }}</p>
    </footer>
</template>

<script>
export default {
    name: 'footer',
    data(){
        return{
            footerText : "Copyright NWMSU 2021 "
        }
    }
}
</script>

<style scoped>
footer{
    background-color: lightgreen;
    padding : 20px;
    text-align: right;
    color: black;

}
</style>