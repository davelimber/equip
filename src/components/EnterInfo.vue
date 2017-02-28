<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <form class="col s12">
      <div class="row">
        <div class="input-field col s6">
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">Company name</label>
        </div>
      </div>
      <div class="row">
        <div class="input-field col s6">
          <input id="icon_telephone" type="tel" class="validate">
          <label for="icon_telephone">Telephone</label>
        </div>
      </div>

      <div class="row">
        <div class="input-field col s6">
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">Street Address</label>
        </div>
      </div>

      <div class="row">
        <div class="input-field col s6">
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">City</label>
        </div>
      </div>

      <div class="row">
        <div class="input-field col s6">
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">State</label>
        </div>
      </div>

      <div class="row">
        <div class="input-field col s6">
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">Zip</label>
        </div>
      </div>


    </form>

  </div>
</template>

<script>
  export default {
    name: 'EnterInfo',
    data() {
      return {
        msg: 'Please Enter Your Company Information'
      }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .placeholder {
    font-size: 36px
  }
  
  #telephone {
    font-size: 36px;
    text-align: center;
  }
</style>