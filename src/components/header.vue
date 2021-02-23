<template>
    <header>
        <h3>
            {{title}}
        </h3>
    </header>
</template>

<script>
export default {
    name: 'header',
    data(){
        return{
            title: "NORTHWEST MISSOURI STATE UNIVERSITY"
        }
    }
}
</script>

<style scoped>
    header{
        background-color: darkgreen;
        padding: 20px;
        height: 50px;
        text-align: left;
        color: white;


    }
</style>