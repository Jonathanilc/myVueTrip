<template>
  <div>
    <h1>Please fill out our form...</h1>
    <form>
      <div id="form-header">
        <slot name="form-header"></slot>
      </div>
      <div id="form-fields">
        <slot name="form-fields"></slot>
      </div>
      <div id="form-controls">
        <slot name="form-controls"></slot>
      </div>
      <div id="useful-links">
        <ul>
          <li><a href="#">link1</a></li>
          <li><a href="#">link2</a></li>
          <li><a href="#">link3</a></li>
          <li><a href="#">link4</a></li>
        </ul>
      </div>
    </form>
  </div>
</template>

<script>


  export default {
    components:{

    },
    data(){
     return {

     }
    },
    methods: {

    }
  }
</script>
