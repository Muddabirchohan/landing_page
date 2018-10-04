<template>

  <div>

    <p> you have {{ myitems }} props </p>
    <form>
      <input
        v-model="name"
        type="text"
        @change="getName"> <br>
      <input
        v-model="email"
        type="text"
        @change="getEmail"> <br>
      <input
        v-model="password"
        type="password"
        @change="getPassword"> <br>

      <b-form-select
        v-model="selected"
        :options="options"
        class="mb-3">
        <template slot="first">
          <!-- this slot appears above the options from 'options' prop -->
          <option
            :value="null"
            disabled>-- Please select an option --</option>
        </template>
        <!-- these options will appear after the ones from 'options' prop -->
        <option value="C">Option C</option>
        <option value="D">Option D</option>
      </b-form-select>
      <div>Selected: <strong>{{ selected }}</strong></div>
      <b-button @click="getData"> Submit</b-button>
    </form>
  </div>


</template>

<script>


  export default {
    data() {
      return {
        name: null,
        email: null,
        password: null,
        selected: null,
        options: [
          { value: 'A', text: 'Option A (from options prop)' },
          { value: 'B', text: 'Option B (from options prop)' }
        ]
      }
    },

    computed: {
      onsubmitdata(){
        return this.name;
        console.log(this.name + '<br>' + this.email + '<br>' + this.password + '<br>' + this.number + '<br>' + this.contact + '<br>'+ this.link)
      }
    },

    methods : {
      getData(){
         console.log(this.name + this.email + this.password);
      },



      getName: function (e) {
        this.name = e.target.value;
        console.log("name" , this.name)
      },

      getEmail(e) {
        this.email = e.target.value;
        console.log("email" + this.email)
      },

      getPassword(e){
        this.password = e.target.value;
        console.log("password" + this.password)

      }
    },



  }


</script>
