<template>
	<div class="login">
		<h3>Sign In</h3>
		<input type="text" placeholder="Email"><br/>
		<input type="password" placeholder="Password"><br/>
		<!-- Button click calls the 'login' function -->
		<button v-on:click="login">Connection</button>
		<p>You don't have an account? You can <router-link to='/sign-up'>create one</router-link></p>
		<p><router-link to='/'>Home</router-link></p>
	</div>
</template>

<script>
  export default {
    name: 'login',
    data: function () {
      return {}
    },
    methods: {
      login: function () {
        // Open the 'dashboard' component/view on button click
        this.$router.replace('dashboard')
      }
    }
  }
</script>

<style scoped>
/* "scoped" attribute limits the CSS to this component only */
</style>