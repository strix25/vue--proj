<template>
  <div id="app">
    <div class="navbar has-shadow">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">MyCompany</a>
        </div>

        <span class="navbar-toggle">
          <span></span>
          <span></span>
          <span></span>
        </span>

        <div class="navbar-end navbar-menu">
          <router-link to ="/" class="navbar-item r-item">Home</router-link>
          <router-link to ="faq" class="navbar-item r-item">Features</router-link>
          <router-link to ="faq" class="navbar-item r-item">About</router-link>
          <router-link to ="faq" class="navbar-item r-item">FAQ</router-link>
          
          <div class="navbar-item">
            <p class="control">
              <a class="button is-primary is-outlined">
                <span class="icon">
                  <i class="fa fa-download"></i>
                </span>
                <span>Join Now</span>
              </a>
            </p>
          </div>

        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'

#app 
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px

</style>
