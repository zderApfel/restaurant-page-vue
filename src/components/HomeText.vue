<template>
  <div id="home-text">
    <h1> {{ msg }} </h1>
    <p>Zach's Borgers is a cutesie-style borger restaurant located in Hell, Michigan. The locals say it is the best 
      (and only) borger place they've ever been to.
    </p>
    <h2>What is a Borger?</h2>
    <p>Zach gets this question a lot, it's asked a lot by many customers, in fact. 
      The fact of the matter is that it's not important what a borger is. They taste good, so why ask? 
      Nobody has ever gotten sick from a borger, and nobody is allergic to them either. 
      It's impossible to say any of those things has happened. So please, just calm down and eat your borger.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HomeText',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
