<template>
 <div class="login">
     <loginComponent />
 </div>
</template>
<script>
// @ is an alias to /src
import loginComponent from "@/components/auth/login.vue";
export default {
     name: "login",
     components: {
        loginComponent
    }
};
</script>
