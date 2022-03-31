<template>   
    <div class="news container">     
        <h2>News</h2>
        <NewsList/>   
    </div> 
</template> 

<script> 
import NewsList from '@/components/NewsList.vue'
export default {   
    data() {     
        return {};   
    }, 
    components: {NewsList}
}; 
</script> 
<style>
body {
    padding-top: 5rem;
}

footer  {
    padding-top: 20px;
}

h2{
padding-left:12px;
}
</style>