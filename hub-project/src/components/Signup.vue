<template>
	<div class="signup">
		<h3>Sign Up</h3>
		<p>Let's create a new account</p>
		<input type="text" placeholder="Email"><br/>
		<input type="password" placeholder="Password"><br/>
		<button>Sign Up</button>
		<p>or go back to <router-link to='/login'>Login</router-link></p>
		<p><router-link to='/'>Home</router-link></p>
	</div>
</template>

<script>
  export default {
    name: 'signup',
    data: function () {
      return {}
    },
    methods: {}
  }
</script>

<style scoped>
/* "scoped" attribute limits the CSS to this component only */
</style>