<template>
    <div> 
        <h1 class="title">Friends List </h1>
        <FriendsVue />

    </div> 
</template>

<script>
import FriendsVue from "./Friends.vue";
export default {
components: {
    FriendsVue
  }
}
</script>

<style>
    h1 {color:gray}
    body {color:coral; background-color:black;border: 2px solid coral}
    .title{color:blue}
</style>