<template>
    <div>
        <app-header></app-header>
        <router-view></router-view>
        <app-footer></app-footer>
    </div>
</template>

<script>
// Imports
//import addBlogs from './components/addBlog.vue';
//import showBlogs from './components/showBlogs.vue';
//import listBlogs from './components/listBlogs.vue';
import header from './components/header.vue';
import footer from './components/footer.vue';
//import singleBlog from './components/singleBlog.vue';


export default {
    components: {
        'app-header': header,
        'app-footer': footer
    },
    data () {
        return {
        }
    },
    methods: {
    }
}
</script>

<style>
body{
    margin: 0;
    font-family: 'Nunito SemiBold';
}
</style>