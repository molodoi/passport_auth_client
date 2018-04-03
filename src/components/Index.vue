<template>
  <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <h1>Index page</h1>
                <div class="text-center">
                    <router-link :to="{ name: 'Register' }" class="btn btn-default">
                        Register
                    </router-link>

                    <router-link :to="{ name: 'Login' }" class="btn btn-default">
                        Login
                    </router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
