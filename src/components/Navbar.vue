<template>
    <div class="navbar">
        <nav class="nav-extended indigo darken-2">
            <div class="nav-content">
                <router-link to="">
                    <span class="nav-title">Ninja Smoothies</span>
                </router-link>
                <a href="" class="btn-floating btn-large halfway-fab pink">
                    <i class="material-icons">add</i>
                </a>
            </div>

        </nav>
    </div>
</template>
<script>
export default {
    name : 'Navbar',
    data(){
        return{

        }
    }

}
</script>
<style>
    .navbar{
        position: fixed;
        top: 0%;
        width: 100%;
    }
</style>

