<template>
  <v-app>
    <v-main>
      <center>
        <div class="container">
          <span><router-link to="/">Home</router-link></span>
          <span><router-link to="/login">Login</router-link></span>
          <span><router-link to="/registration">Registration</router-link></span>
          <span><router-link to="/weathersearch">Weather Search</router-link></span>
          <span><router-link to="/profile">Profile</router-link></span>
        </div>
      </center>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
}
</script>

<style>
.container span{
  padding: 15px;
}

.container{
  margin-top: 20px;
}
</style>
