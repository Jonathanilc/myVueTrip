<template>
  <div>

    <!--<app-header v-bind:title="title" v-on:changeTitle="updateTitle($event)"></app-header>-->

    <!--<app-ninjas v-bind:ninjas="ninjas"></app-ninjas>-->

    <!--<app-footer v-bind:title="title"></app-footer>-->

    <!--<ninjas></ninjas>-->
    <!--<p>{{greeting()}}</p>-->

    <!--<form-helper>-->
      <!--<div slot="form-header">-->
        <!--<h3>This is the title of the form</h3>-->
        <!--<p>Information about the form</p>-->
      <!--</div>-->
      <!--<div slot="form-fields">-->
        <!--<input type="text" placeholder="name" required>-->
        <!--<input type="password" placeholder="password" required>-->
      <!--</div>-->
      <!--<div slot="form-controls">-->
        <!--<button v-on:click="handleSubmit">Submit</button>-->
      <!--</div>-->
    <!--</form-helper>-->
    <!--<keep-alive>-->
      <!--<component v-bind:is="component"></component>-->
    <!--</keep-alive>-->
    <!---->
    <!--<button v-on:click="component='form-one'">Show form one</button>-->
    <!--<button v-on:click="component='form-two'">Show form two</button>-->
    <add-blog></add-blog>

  </div>
</template>

<script>

//import Header from './components/Header.vue';
//import Footer from './components/Footer.vue';
//import Ninjas from './components/Ninjas.vue';
//import formOne from './components/formOne.vue'
//import formTwo from './components/formTwo.vue'
import addBlog from './components/addBlog.vue'

export default {

//  components:{
//    'ninjas':Ninjas
//  },

  components:{

//    'app-header': Header,
//    'app-footer': Footer,
//    'app-ninjas': Ninjas
//    'form-one':formOne,
//    'form-two':formTwo
    'add-blog':addBlog
  },
  data () {
    return {
//      component:'form-two'
//      title: 'i am the dynamic slot title'
//      ninjas: [
//        {name:'Ryu',speciality:'Vue Components',show:false},
//        {name:'Crystal',speciality:'Html Wizardry',show:false},
//        {name:'Hitoshi',speciality:'Click Events',show:false},
//        {name:'Tango',speciality:'Conditional',show:false},
//        {name:'Kami',speciality:'Webpack',show:false},
//        {name:'Yoshi',speciality:'Data Diggin',show:false}
//      ],
//      title:'Vue Ninjas'

    }
  },
  methods:{
//    greeting: function () {
//      return 'heeeeeey cowboy!';
//    }

//    updateTitle: function (updatedTitle) {
//      this.title = updatedTitle;
//    }
  }
}
</script>

<style>
body{
  margin:0;
  font-family: 'Nunito SemiBold';
}
#add-blog *{
  margin: 20px auto;
  max-width: 500px;
}
</style>
