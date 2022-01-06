<template>
  <div>
    <nav>
      <div class="nav-wrapper">
        <a href="#" data-target="slide-out" class="sidenav-trigger show-on-large"><i class="material-icons">menu</i></a>
        <a href="#!" class="brand-logo">Logo</a>
        <form class="right hide-on-med-and-down">
          <div class="input-field">
            <input id="autocomplete-input" type="search" placeholder="Pesquisar ..." required>
            <label class="label-icon" for="autocomplete-input" style="margin-top:-10px; padding-left:20px; height:20px;"><i class="material-icons">search</i></label>
            <i class="material-icons">close</i>
          </div>
        </form>
        
        <ul class="right hide-on-med-and-down">
          <li><a href="sass.html">Link 1</a></li>
          <li><a href="badges.html">Link 2</a></li>
          <li><a href="collapsible.html">Link 3</a></li>
          <li><a href="mobile.html">Link 4</a></li>  
        </ul>
        
      </div>
    </nav>
    <ul id="slide-out" class="sidenav">
      <li><div class="user-view">
        <div class="background">
          <img src="https://materializecss.com/images/office.jpg">
        </div>
        <a href="#user"><img class="circle" src="https://materializecss.com/images/yuna.jpg"></a>
        <a href="#name"><span class="white-text name">John Doe</span></a>
        <a href="#email"><span class="white-text email">jdandturk@gmail.com</span></a>
      </div></li>
      <li><a href="#!"><i class="material-icons">cloud</i>First Link With Icon</a></li>
      <li><a href="#!">Second Link</a></li>
      <li><div class="divider"></div></li>
      <li><a class="subheader">Subheader</a></li>
      <li><a class="waves-effect" href="#!">Third Link With Waves</a></li>
    </ul>
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
