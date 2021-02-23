<template>
    <div>
        <header>{{title}}</header>
            <div>{{content}}</div>
    </div>
</template>
<script>
export default {
    name: 'comp',
    data(){
        return{
            title:'Components',
            content: 'Creating Components in Vue (TEST)'
        }
    }
}
</script>