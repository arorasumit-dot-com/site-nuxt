<template>
  <div class="ma0 pa0 home h-100 flex flex-column justify-center white w-100 vh-100">
    <p class="f-headline-ns f1 tc ma4">Hi, I am Sumit Arora</p>
    <p class="f-subheadline-ns f2 tc ma4">a full stack developer at rangle.io</p>
    <div class="tc ma4">
      <a href="https://twitter.com/arorasumit">
        <i class="fab fa-twitter fa-3x white"/>
      </a>
      &nbsp;&nbsp;
      <a href="https://github.com/sumitarora">
        <i class="fab fa-github fa-3x white"/>
      </a>
      &nbsp;&nbsp;
      <a href="https://linkedin.com/in/arorasumit85">
        <i class="fab fa-linkedin fa-3x white"/>
      </a>
      &nbsp;&nbsp;
      <a href="#">
        <i class="fas fa-envelope fa-3x white"/>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
.home {
  background-color: #fe4365;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
