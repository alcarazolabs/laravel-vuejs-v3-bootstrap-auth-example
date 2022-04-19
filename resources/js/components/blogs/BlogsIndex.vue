<template>
    
     <h1>Blogs Index</h1>
    <router-link :to="{ name: 'blogs.contact' }" class="btn btn-primary">Contacto</router-link>


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
