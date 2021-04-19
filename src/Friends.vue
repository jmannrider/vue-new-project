<template>
    <div> 
    
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
