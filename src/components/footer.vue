<template>
    <footer>
        <p>Copyright 2020 XrisDwhyner Blog</p>
    </footer>
</template>
<script>
export default {
    props: {
      title: {
        type: String,
        required: true
      }
    },
    data(){
        return{
        }
    }
}
</script>
<style scoped>
footer{
    background: #222;
    padding: 6px;
    position: fixed;
    left: 0;
    bottom: 0;
     height:20px;
    width: 100%;
}
p{
        color: #e4eee4;
        text-align: center;
}
</style>