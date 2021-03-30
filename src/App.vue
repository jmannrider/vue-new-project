<template>
    <div> 
        <h1>Friends List</h1>
        <ul>
            <li v-for="i in friends" :key="i">
                {{i}}
            </li>
        </ul>

    </div> 
</template>

<script>
export default { 
    data() { 
    return { 
        friends:["Manny", "Sabika", "Sam"]   
    }; 
    } 
}
</script>

<style>
    h1 {color:gray}
    body {color:coral; background-color:black;border: 2px solid coral}
</style>