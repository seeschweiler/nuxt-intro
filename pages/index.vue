<template>
  <div class="container">
    <div class="alert alert-warning alert-dismissible" role="alert">
      <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
      <strong><a href="http://codingthesmartway.com/courses/vuejs2-complete-guide" target="_blank">[ONLINE COURSE] - Vue.js 2 - The Complete Guide</a></strong> +++ Understand the Theory behind Vue.js and use it in Real Projects. +++  Build amazing Vue.js Applications - all the Way from Small and Simple Ones up to Large Enterprise-level Ones +++ Leverage Vue.js in both Multi- and Single-Page-Applications (MPAs and SPAs) +++
    </div>
    <section class="container2">
      <div>
        <logo/>
        <h1 class="title">
          NUXT
        </h1>
        <h2 class="subtitle">
          Routes
        </h2>
        <div class="links">
          <a href="home" target="_blank" class="button--green">Home</a>
          <a href="home/about" target="_blank" class="button--grey">About</a>
        </div>
      </div>
    </section>
    <br/><br/><hr/>
     <div class="footer">
       <p>&copy <a href="http://codingthesmartway.com" target="_blank">CodingTheSmartWay.com</a> | <a href="http://codingthesmartway.com/imprint" target="_blank">Imprint</a></p>
     </div>
  </div>
</template>

<script>
import Logo from '~components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container{
  padding-top: 10px
}

.container2
{
  min-height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
