<template>

        <h1>Blog Contact</h1>
         <router-link :to="{ name: 'blogs.index' }" class="btn btn-primary">Index</router-link>

</template>


<script>
import { reactive } from "vue";

export default {

    setup(){
         const contact = reactive({
            'name': '',
            'email': '',
           
        })

        return {
            contact
        }
    }
}
</script>
