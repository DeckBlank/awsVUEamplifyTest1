<template>
    <amplify-authenticator>
    <!-- The rest of your app code -->
    <amplify-sign-out></amplify-sign-out>
    <router-link :to="{ name: 'Home' }">Home</router-link>
    <br>
    <br>
    <router-link :to="{ name: 'Productos' }">Productos</router-link>
  </amplify-authenticator>
</template>
<script>
export default {
    
}
</script>