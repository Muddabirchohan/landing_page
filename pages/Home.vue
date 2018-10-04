<template>
  <div>

    <!--<div class="css3-notification">-->
    <!--<p>Hi, this is a notification and it bounces.</p>-->
    <!--</div>-->
    <div
      id="top"
      class="frontimage js-cd-top">

      <div style="color: white; position: fixed">
        Window width: {{ windowWidth }}
        <br> Window height: {{ windowHeight }}
        <!--<br> Find Top: {{ findTop }}-->
      </div>



      <!--<b-button-->
      <!--id="buttonfade"-->
      <!--@click="scrollSmoothToBottom"> bottom-->
      <!--</b-button>-->
      <b-container>
        <b-row>
          <b-col
            sm="12"
            lg="6"
            md="6">
            <img
              src="./../assets/tradebakerzlogo.png"
              class="logofront">
            <img>
            <h1 class="head1"> <b> Instant WooCommerce <br> To React Native Mobile <br> Templates </b>
            </h1>
          </b-col>
          <b-col
            sm="12"
            lg="6"
            md="6">

            <div
              style="padding-top: 80px"
              class="custom-links">
              <b-link
                to="home"
                style="color: white;">Home</b-link>
              <b-link
                to="features"
                style="color: white;">Features</b-link>
              <b-link
                to="screenshots"
                style="color: white;">Screenshots</b-link>
              <b-link
                to="aboutus"
                style="color: white;">About-us</b-link>
              <b-link
                to="demowebapp"
                style="color: white;">Demo WebApp</b-link>
              <b-link
                to="packages"
                style="color: white;">packages</b-link>
              <b-link
                to="contactus"
                style="color: white;">contact-us</b-link>
            </div>

            <!--<div-->
            <!--v-show="upHere"-->
            <!--class="dropdown">-->
            <!--<b-dropdown-item-button >I'm a button</b-dropdown-item-button>-->
            <!--<b-dropdown-item-button>I'm also a button</b-dropdown-item-button>-->
            <!--<b-dropdown-item-button disabled>I'm a button, but disabled!</b-dropdown-item-button>-->
            <!--<b-dropdown-item-button>I don't look like a button, but I am!</b-dropdown-item-button>-->
            <!--</div>-->
            <img
              src="./../assets/frontimage.png"
              width="90%"
              class="firstcell">
            <img>
          </b-col>
        </b-row>
      </b-container>
    </div>


    <b-container >
      <div class="about-us">
        <h1> <b> ABOUT TRADEBAKERZ </b> </h1>
        <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing </p>
      </div>
      <b-row
        class="centerimages"
        style="padding-bottom: 50px">
        <b-col
          md="4"
          lg="4"
          sm="12"
        >
          <div class="bg3for3">
            <img
              src="./../assets/workfromeverywhere.png"
              class="small"
              style="padding-left: 50px; width: 120px; margin-top: 10px"> <img> <br><br>
          </div>
          <h6 class="bg3head"> Work From Everywhere </h6>
          <p class="parasilver"> Lorem ipsum dolor sit amet, labore et dolore magna aliqua. Ut enim ad minim veniam,  </p>

        </b-col>

        <b-col
          md="4"
          lg="4"
          sm="12"
        >
          <div class="bg3for3">
            <img
              src="./../assets/manageschedule.png"
              class="small"
              style="padding-left: 50px; width: 120px; margin-top: 10px"> <img> <br><br>
          </div>
          <h6 class="bg3head"> Manage Your Schedule </h6>
          <p class="parasilver"> Lorem ipsum dolor sit amet, consectetur labore et dolore magna aliqua. Ut enim ad minim veniam,   </p>
        </b-col>


        <b-col
          md="4"
          lg="4"
          sm="12">
          <div class="bg3for3">
            <img
              src="./../assets/increase.png"
              class="small"
              style="padding-left: 40px; width: 120px; margin-top: 10px"> <img> <br>
          </div>
          <h6 class="bg3head"> Increase Your Work Rates </h6>
          <p class="parasilver"> Lorem ipsum dolor sit labore et dolore amet, labore et dolore magna aliqua. Ut enim ad minim veniam,   </p>

        </b-col>
      </b-row>
    </b-container>


    <div class="bgintuitive">
      <b-container>
        <b-row style="padding-bottom: 200px">
          <b-col>
            <div>
              <h2 class="orangehead ">
                <span class="orange"> <b> INTUITIVE  </b> </span>
                DESIGN <br> AND <span class="orange"> <b> UX FLOWS </b> </span>
              </h2>
              <p class="orangehead2">
                we know how much a good desigh adds to a website Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
              </p>
            </div>
          </b-col>
          <b-col>
            <div class="intuitive-image">
              <img
                src="./../assets/doublecell.png"
                width="100%"
                class="margindouble">
              <img>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>


    <div
      class="reactnativetemplateimage"
      style="padding-bottom: 50px">
      <div>
        <b-container>
          <b-row >
            <b-col lg="6">
              <div class="reactNative-image">
                <img
                  src="./../assets/reactnativetempimage1.png"
                  width="240px"
                  height="500px"
                >
                <img>
                <img
                  src="./../assets/reactnativetempimage2.png"
                  width="250px"
                  height="520px">
                <img>
              </div>
            </b-col>
            <b-col
              lg="6">
              <div class="textmarginreactnative">
                <h2 >
                  <span class="orange reactnativetext googlefont"> <b> REACT NATIVE </b> </span> <br> <b class="textgooglenormal"> TEMPLATE </b>
                </h2>
                <p> There are many variations of passages of Lorem Ipsum available, <br> but the majority have suffered alteration in some form, by injected humour.
                </p>
              </div>
            </b-col>
          </b-row>
        </b-container>
      </div>
    </div>


    <div>
      <b-container>
        <b-row style="padding-bottom: 300px">
          <b-col
            lg="6"
            md="6"
          >
            <div>
              <h1 class="unlimitedproductstext">  UNLIMITED <br> PRODUCTS WITH <br>  <span class="orange"> <b> INFINITE SCROLLING </b> </span>
              </h1>
              <p class="unlimitedproductspara">
                Add unlimited products to our app ios and android with multiple features
                Add unlimited products to our app ios and android with multiple features
                Add unlimited products to our app ios and android with multiple features
              </p>
            </div>
          </b-col>

          <b-col
            lg="6"
            md="6">
            <div
              class="bgunlimitedproducts">
              <img
                src="./../assets/unlimitedproductsimage.png"
                width="100%">
              <img>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>



    <div>
      <b-container>
        <b-row class="paymentgateways">
          <b-col
            lg="6"
            sm="12"
            md="6">
            <img
              src="./../assets/paymentgateway.png"
              width="80%"><img>
          </b-col>

          <b-col
            lg="6"
            sm="12"
            md="6">
            <div>
              <h1> <span
                class="googlefont"
                style="color: #ff9c2f">  PAYMENT </span>  <Span class="textgooglenormal"> GATEWAYS </Span> </h1>
              <p> There are many variations of passages of Lorem Ipsum available There are many variations of passages of Lorem Ipsum available There are many variations of passages of Lorem Ipsum available</p>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>


    <div class="bgpink">
      <h1 class="packgaes-head"> PACKAGES </h1>
      <b-container >
        <b-row style="padding-bottom: 50px">
          <b-col>
            <div
              class="package">
              <div
                class="package-content">
                <h4 > STANDARD TEMPLATE</h4>
                <p> <b>  <sup>$ </sup> 69  </b>  </p>
                <ul>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>  Full integration with woo commerce
                  </li>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>   Full functional ios <br> and react native template
                  </li>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>  unlimited support and updating
                  </li>
                </ul>
                <b-button> Buy now</b-button>
              </div>
            </div>
          </b-col>
          <b-col
            md="6">
            <div class="package">
              <div class="package-content">
                <h4> CUSTOM </h4>
                <p> <b>  <sup>$ </sup> 199  </b>  </p>
                <ul>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>  Full integration with woo commerce
                  </li>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>  Full functional ios <br> and react native template
                  </li>
                  <li>
                    <span style="color: orange; font-size: 20px"> <b> ✓ </b> </span>  unlimited support and updating
                  </li>
                </ul>
                <b-button> Contact Us </b-button>
              </div>
            </div>
          </b-col>

        </b-row>
      </b-container>
    </div>


    <div
      class="bgscreenshots"
      style="padding-bottom: 100px">
      <div> <h1 class="screenshots "> SCREENSHOTS </h1></div>
      <img
        src="./../assets/screenshot.png"
        class="logotradebakerz">
      <img>
    </div>



    <div class="bg2">
      <div >
        <h1 > <b class="demo-head"> DEMO APPS DOWNLOAD </b> </h1>
        <b-row style="margin-right: 0px">
          <b-col>
            <div class="demoapps">
              <p>
                <img
                  src="./../assets/applesmall.png">
                <img>
                <span class="googleandapple"> Available on  </span> <br>
                <span
                  class="googleandapple"
                  style="padding-left: 40px"> <b> APPLE  STORE </b> </span>
              </p>
            </div>
          </b-col>
          <b-col>
            <div class="demoapps">
              <p>
                <img
                  src="./../assets/googleplaysmall.png">
                <img>
                <span class="googleandapple"> Available on  </span> <br>
                <span
                  class="googleandapple"
                  style="padding-left: 40px"> <b> GOOGLE PLAY </b> </span>
              </p>
            </div>
          </b-col>
        </b-row>
      </div>
    </div>

    <div class="contactus">
      <h1
        class="contactheading"
        style="text-align: center">
        Contact Us
      </h1>
      <div>
        <b-container >
          <b-row>
            <b-col
              md="6"
              sm="12">
              <img
                src="./../assets/mapphone.png"
                width="90%">
              <img>
            </b-col>




            <form @submit="onsubmitdata">
              <b-col
                class="formpad">
                <b-row >

                  <b-col
                    md="6"
                    sm="12">
                    <label>
                      <b-form-input
                        v-model="name"
                        type="text"
                        placeholder="Enter your name"
                        class="roundinput"
                        required/>
                    </label>
                    <label>
                      <b-form-input
                        v-model="contact"
                        type="number"
                        placeholder="Enter contact "
                        class="roundinput"
                        required/>
                    </label>
                  </b-col>

                  <b-col>
                    <label>
                      <b-form-input
                        v-model="email"
                        type="email"
                        placeholder="Enter  email"
                        class="roundinput"
                        required/>
                    </label>
                    <label>
                      <b-form-select
                        v-model="selected"
                        :options="options"
                        class="roundinput" />

                    </label>
                  </b-col>

                </b-row>
                <b-form-textarea
                  v-model="mytextarea"
                  :rows="5"
                  :max-rows="8"
                  placeholder="Enter something"
                  class="roundinput"
                  required/>
                <b-button
                  type="submit"
                  class="customButton"> Send </b-button>
              </b-col>

            </form>
          </b-row>




        </b-container>
      </div>

    </div>



    <div class="bottomImage">
      <img
        src="./../assets/tradebakerzlogo.png"
        class="logotradebakerz"><img>
    </div>

    <div class="container">
      <p class="ending"> © 2018 All Rights Reserved </p>
    </div>


    <div v-if="(mb > windowHeight+400)">
      <div
        v-if="show"
        class="topbutton css3-notification">
        <a
          href="#top" >
          top
        </a>
      </div>
    </div>

  </div>
</template>

<script>

  import Navbar from './Navbar.vue';
  export default {

    components: {
      Navbar
    },

    data() {
      return {
        name: '',
        email: '',
        contact: '',
        subject: '',
        mytextarea: '',
        isShowing: false,
        show: true,
        show2: false,
        windowWidth: 0,
        windowHeight: 0,
        mb: 7, //offset
        height: 0,
        selected: null,
        options: [
          { value: null, text: 'Please select an option' },
          { value: 'a', text: 'This is First option' },
          { value: 'b', text: 'Selected Option' },
          { value: {'C': '3PO'}, text: 'This is an option with object value' },
          { value: 'd', text: 'This one is disabled', disabled: true }
        ]
      }
    },

    mounted() {
      window.onscroll = () => {
        var d = document.documentElement;
        var offset = d.scrollTop + window.innerHeight;
        var height = d.offsetHeight;
         this.mb = offset;
         this.height = height;
      },

        this.$nextTick(function() {
        window.addEventListener('resize', this.getWindowWidth);
        window.addEventListener('resize', this.getWindowHeight);

        //Init
        this.getWindowWidth()
        this.getWindowHeight()
      })
    },

    beforeDestroy() {
      window.removeEventListener('resize', this.getWindowWidth);
      window.removeEventListener('resize', this.getWindowHeight);
    },

      methods: {

        onsubmitdata(e){
          console.log(this.name + '\n' + this.email + '\n' + this.contact + '\n' + this.selected + '\n' + this.mytextarea )
          e.preventDefault();
          this.name ="";
          this.email ="";
          this.contact ="";
          this.mytextarea ="";
        },

        toggleShow() {
          this.isShowing = !this.isShowing;
        },

        getWindowWidth(event) {
          this.windowWidth = document.documentElement.clientWidth;
        },

         getWindowHeight(event) {
          this.windowHeight = document.documentElement.clientHeight;
        },

        // topFunction: function () {
        //   document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
        // },

        // scrollSmoothToBottom: function () {
        //   window.scrollTo(0, 800);
        // },
  },

    }
</script>


<style>

  @import url('https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i');
  @import url('https://fonts.googleapis.com/css?family=Work+Sans');
  @keyframes bounce {

    0% {
      transform:translateY(-100%);
      opacity: 0;
    }
    5% {
      transform:translateY(-100%);
      opacity: 0;
    }
    15% {
      transform:translateY(0);
      padding-bottom: 5px;
    }
    30% {
      transform:translateY(-50%);
    }

    40% {
      transform:translateY(0%);
      padding-bottom: 6px;
    }

    50% {
      transform:translateY(-30%);
    }

    70% {
      transform:translateY(0%);
      padding-bottom: 7px;
    }
    80% {
      transform:translateY(-15%);
    }
    90% {
      transform:translateY(0%);
      padding-bottom: 8px;
    }
    95% {
      transform:translateY(-7%);
    }
    97% {
      transform:translateY(0%);
      padding-bottom: 9px;
    }
    99% {
      transform:translateY(-3%);
    }
    100% {
      transform:translateY(0);
      padding-bottom: 9px;
      opacity: 1;
    }
  }


  .css3-notification {

    -webkit-animation: bounce 1.5s ease-out;
    -moz-animation: bounce 1000ms ease-out;
    -o-animation: bounce 1000ms ease-out;
    animation: bounce 1.5s ease-out;
  }

  .bounce-enter-active {
    animation: bounce-in .5s;
  }
  .bounce-leave-active {
    animation: bounce-in .5s reverse;
  }
  @keyframes bounce-in {
    0% {
      transform: scale(0);
    }
    50% {
      transform: scale(1.5);
    }
    100% {
      transform: scale(1);
    }
  }

  .topbutton{
    position: fixed;
    background-color: darkslategray;
    color: white;
    text-transform: uppercase;
    font-size: 20px;
    bottom: 20px;
    width: 60px;
    height: 35px;
    right: 10px;
    border-radius: 20%;
    text-align: center;

  }

  .head1{
    color: white;
    font-family: 'Ubuntu', sans-serif;
    padding-top: 250px;
    font-size: 45px;
    text-align: center;
  }

  .firstcell{
    padding-top: 50px;
  }

  .frontimage{
    background-image: url('./../assets/background.jpg');
    width: 100%;
  }

  .bg2 {

    display: flex;
    flex-direction: row;
    align-content: center;
    justify-content: center;
    padding-top: 20px;
    padding-bottom: 100px;
    background-image: url('./../assets/bg2.png');
    width: 100%;
  }



  .bg2 h1{
    color: white;
    text-align: center;
    font-size: 35px;
    font-family: 'Ubuntu', sans-serif;
  }
  .bottomImage{
    background-image: url('./../assets/endbg.png');
    width: 100%;
  }

  .ending {
    font-size: 15px;
    color: blue;
    text-align: center;
    font-family: 'Work Sans', sans-serif;
    color: rgb(34, 80, 129);
  }


  .centerimages{
    margin-left: 20px;
    margin-top: 50px;
  }

  .parasilver{
    margin-top: 30px;
    color: #7f828b;
  }
  .orangehead{
    float: right;
    margin-top: 200px;
    font-family: 'Ubuntu', sans-serif;
    font-size: 50px;
  }
  .orangehead2{
    margin-left: 100px;
    float: right;
    margin-top: 20px;
    font-size: 20px;
    color: rgba(113, 115, 126, 0.99);
  }


  .orange{
    color: #ff9e07;
  }

  .margindouble{
    padding-top: 50px;
  }

  .reactnativetext{
    margin-top: 350px;
  }
  .textmarginreactnative{
    margin-right: 30px;
    margin-top: 150px;
  }
  .unlimitedproductstext{
    margin-top: 100px;
    float: right;
    font-size: 45px;
    font-family: 'Ubuntu', sans-serif;
  }

  .paymentgateways{
    padding-top: 150px;
  }

  .package{
    background: #FFFFFF;
    border-top: 5px solid darkorange;
    border-radius: 8px;
    box-shadow: 0 5px 25px -13px rgb(0, 0, 0);
    width: 350px;
    height: 600px;
  }

  .package .package-content h4{
    text-align: center;
    padding-bottom: 100px;
    padding-top: 50px;
  }

  .package .package-content button{
    display: block;
    margin-left: auto;
    margin-right: auto;
    background-color: rgb(255, 144, 23);
    font-size: 20px;
    width: 150px;
    height: 40px;
    color: whitesmoke;
    border-radius: 20px;
  }

  .package .package-content {
    align-content: center;
    align-items: center;
  }


  .package .package-content ul{
    margin: 0;
    padding-bottom: 100px;
    padding-top: 30px;
    list-style: none;
  }
  .package .package-content ul li{
    text-align: center;

  }
  .package .package-content p{
    text-align: center;
    color: darkorange;
    font-size: 70px;
    font-family: 'Ubuntu', sans-serif;;
  }
  .logotradebakerz{
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 25%;
    margin-top: 30px;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .contactus{
    margin-top: 70px;
  }


  .bgpink{
    background-image: url('./../assets/pinkbg.png');
    width: 100%;
    background-repeat: no-repeat;
  }
  .logofront{
    margin-top: 50px;
    width: 250px;
    margin-left: 50px;
  }
  .bgunlimitedproducts{
    background-image: url('./../assets/circle2.png');
    background-repeat: no-repeat;
    background-position-x: 50px;
    width: 100%;
  }

  .formpad{
    margin-top: 50px;
  }

  .bgscreenshots{
    background-image: url('./../assets/screenshotbackgroun.png');
    background-size: auto;
    background-repeat: no-repeat;
    margin-top: 50px;
    background-position-x: 35px;
    background-position-y: 105px;
  }


  .bg3for3{
    background-image: url('./../assets/bg3for3.png');
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
  }


  .screenshots{
    text-align: center;
  }

  .bg3head{
    margin-top: 50px;
  }

  .googlefont{
    font-size: 50px;
    font-family: 'Ubuntu', sans-serif;
  }
  .unlimitedproductspara{
    margin-top: 30px;
    float: right;
    margin-left: 100px;
    font-size: 20px;
    color: #7d818d;
  }

  .textgooglenormal{
    font-family: 'Ubuntu normal', sans-serif;
    font-size: 40px;
  }

  .reactnative-image img{
    display: block;
    margin-right: auto;
    margin-left: auto;
  }


  .reactnativetemplateimage{
    background-image: url('./../assets/bg4.png');
    background-size: auto;
    background-position-y: 100px;
    background-repeat: no-repeat;
  }
  .contactheading{
    font-size: 50px;
    font-family: 'Ubuntu', sans-serif;
    color: #2e468c;
    text-transform: uppercase;
  }
  .customButton{
    background-color: rgb(34, 80, 129);
    width: 100%;
    border-radius: 20px;
    margin-top: 30px;
    text-align: center;
  }

  .roundinput{
    border-radius: 20px;

  }

  .bgintuitive{
    background-image: url('./../assets/circle2.png');
    background-size: auto;
    background-repeat: no-repeat;
    background-position-x: -300px;
  }

  .packgaes-head{
    text-align: center;
    margin-bottom: 100px;
  }
  .about-us {
    text-align: center;
    margin-top: 50px;
  }

  .about-us h1{
    color: orange;
    font-family: 'Ubuntu', sans-serif;
    padding-bottom: 50px;
  }

  .demoapps{
    background-color: rgb(244, 244, 244);
    box-shadow: 0px 1px 20px 0px rgba(0, 0, 0, 0.2);
    width: 296px;
    height: 93px;
    border-radius: 50px;
    margin-top: 30px;
  }

  .demoapps p{
    text-align: center;
    padding-top: 10px;
  }

  .googleandapple{
    padding-left: 10px;
    font-size: 20px;
    font-family: WorkSans;
    color: rgb(34, 80, 129);
    font-family: 'Ubuntu', sans-serif;
  }
  .dropdown-item{
    color: white;
  }

  @media (min-width:320px ) and (max-width: 767px) {
    @import url('https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i');
    @import url('https://fonts.googleapis.com/css?family=Work+Sans');

    .custom-links{
     padding-top: 10px;
    }

    .head1{
      color: white;
      font-family: WorkSans;
      font-size: 25px;
      display: block;
      padding-top: 20px;
      margin-left: auto;
      margin-right: auto;
      text-align: center;
    }

    .firstcell{
      padding-top: 20px;
      width: 90%;
    }

    .frontimage{
      background-image: url('./../assets/background.jpg');
      width: 100%;
    }

    .bg2 {
      display: flex;
      flex-direction: row;
      align-content: center;
      justify-content: center;
      padding-top: 20px;
      padding-bottom: 100px;
      background-image: url('./../assets/bg2.png');
      width: 100%;
      margin-left: 0;
      margin-right: 0;
    }

    .bg2 h1{
      color: white;
      text-align: center;
      font-size: 35px;
      font-family: 'Ubuntu', sans-serif;
    }
    .bottomImage{
      background-image: url('./../assets/endbg.png');
      width: 100%;
      padding-bottom: 0px;
    }


    .ending {
      font-size: 15px;
      color: blue;
      text-align: center;
      font-family: 'Work Sans', sans-serif;
      color: rgb(34, 80, 129);
    }




    .centerimages{
      margin-left: 0px;
      margin-top: 50px;
    }

    .parasilver{
      margin-top: 30px;
      text-align: center;
      margin-left: auto;
      margin-right: auto;
      color: #7f828b;

    }
    .orangehead{
      text-align: center;
      margin-top: 200px;
      font-family: 'Ubuntu', sans-serif;
      font-size: 50px;

    }
    .orangehead2{

      font-size: 20px;
      text-align: center;
      margin-left: 0px;

    }


    .orange{
      color: #ff9e07;
    }


    .intuitive-image{
       display: block;
      margin-left: auto;
      margin-right: auto;
    }


    .margindouble{
      width: 350px;
    }

    .reactnativetext{
      margin-top: 370px;
    }
    .textmarginreactnative{
      text-align: center;
      margin-top: 20px;
      margin-right: 0px;
    }
    .unlimitedproductstext{
      margin-top: 100px;
      float: right;
      font-size: 45px;
      font-family: 'Ubuntu', sans-serif;
      text-align: center;
    }

    .paymentgateways{
      text-align: center;
      padding-bottom: 100px;
      padding-top: 0px;
    }

    .package{
      background: #FFFFFF;
      border-top: 5px solid darkorange;
      border-radius: 8px;
      box-shadow: 0 5px 25px -13px rgb(0, 0, 0);
      width: 100%;
    }

    .package .package-content h4{
      text-align: center;
      padding-bottom: 50px;
      padding-top: 50px;
    }

    .package .package-content button{
      display: block;
      margin-left: auto;
      margin-right: auto;
      background-color: rgb(255, 144, 23);
      font-size: 10px;
      width: 100px;
      height: 40px;
      color: whitesmoke;
      border-radius: 20px;
    }

    .package .package-content {
      align-content: center;
      align-items: center;
    }


    .package .package-content ul{
      margin: 0;
      padding-bottom: 100px;
      padding-top: 30px;
      list-style: none;
      padding-left: 0px;
    }
    .package .package-content ul li{
      text-align: center;
    }
    .package .package-content p{
      text-align: center;
      color: darkorange;
      font-size: 70px;
      font-family: 'Ubuntu', sans-serif;;
    }
    .logotradebakerz{
      display: block;
      margin-left: auto;
      margin-right: auto;
      margin-top: 20px;
      padding-top: 30px;
      padding-bottom: 10px;
    }

    .contactus{
      display: block;
      margin-right: auto;
      margin-left: auto;
      padding-left: 0px;
      padding-right: 0px;
      width: 300px;
    }

    .bgpink{
      background-image: url('./../assets/pinkbg.png');
      width: 100%;
      background-repeat: no-repeat;
    }
    .logofront{
      width: 150px;
      margin-left: 50px;
    }
    .bgunlimitedproducts{
      background-image: url('./../assets/circle2.png');
      background-repeat: no-repeat;
      background-position-x: 50px;
      width: 100%;
    }

    .bgscreenshots{
      background-image: url('./../assets/screenshotbackgroun.png');
      background-size: auto;
      background-repeat: no-repeat;
      margin-top: 50px;
      background-position-x: 35px;
      background-position-y: 105px;
    }

    .bg3for3{
      background-image: url('./../assets/bg3for3.png');
      background-size: auto;
      background-repeat: no-repeat;
      margin-top: 50px;
    }

    .screenshots{
      text-align: center;
    }

    .bg3head{
      margin-top: 50px;
      text-align: center;
    }

    .googlefont{
      font-size: 50px;
      font-family: 'Ubuntu', sans-serif;
      text-align: center;
    }
    .unlimitedproductspara{
      margin-top: 30px;
      margin-left: 0px;
      font-size: 20px;
      color: #7d818d;
      text-align: center;
    }

    .textgooglenormal{
      font-family: 'Ubuntu normal', sans-serif;
      font-size: 40px;
    }

    .reactnativetemplateimage{
      background-image: url('./../assets/bg4.png');
      background-size: auto;
      background-position-y: 100px;
      background-repeat: no-repeat;
    }
    .contactheading{
      font-size: 50px;
      font-family: 'Ubuntu', sans-serif;
      color: #2e468c;
    }
    .customButton{
      background-color: rgb(34, 80, 129);
      border-radius: 20px;
      margin-top: 30px;
      display: block;
      width: 100%;
      margin-left: auto;
      margin-right: auto;
    }

    .roundinput{
      border-radius: 20px;
      margin-left: 20px;
      padding-left: 10px;
    }

    .bgintuitive{
      background-image: url('./../assets/circle2.png');
      width: 100%;
      background-repeat: no-repeat;
      background-position-x: -300px;
    }

    .packgaes-head{
      text-align: center;
      margin-bottom: 100px;
    }
    .about-us {
      text-align: center;
      margin-top: 50px;
    }

    .about-us h1{
      color: orange;
      font-family: 'Ubuntu', sans-serif;
      padding-bottom: 50px;
      font-size: 35px;
    }

    .demoapps{
      background-color: rgb(244, 244, 244);
      box-shadow: 0px 1px 20px 0px rgba(0, 0, 0, 0.2);
      border-radius: 50px;
      margin-top: 20px;
      margin-left: auto;
      margin-right: auto;
      width: 160px;
      height: 70px;
    }

    .demoapps p{
      text-align: center;
      padding-top: 2px;
      font-size: 7px;
      text-align: center;
    }

    .googleandapple{
      padding-left: 10px;
      font-size: 12px;
      font-family: WorkSans;
      color: rgb(34, 80, 129);
      font-family: 'Ubuntu', sans-serif;
    }

    .small{
      padding-left: 0px;
      padding-top: 20px;
      width: 380px;
      height: 70px
    }

    .demo-head{
      font-size: 15px;
    }

    .reactNative-image{
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 220px;
      padding-left:0px;
      padding-right: 0px;
    }
  }

  @media (min-width:768px ) and (max-width: 991px) {
    @import url('https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i');
    @import url('https://fonts.googleapis.com/css?family=Work+Sans');

    .head1{
      color: white;
      font-family: 'Ubuntu', sans-serif;
      padding-top: 250px;
      font-size: 30px;
      text-align: center;
    }

    .firstcell{
      padding-top: 50px;
      width: 300px
    }

    .frontimage{
      background-image: url('./../assets/background.jpg');
      width: 100%;
    }

    .bg2 {

      display: flex;
      flex-direction: row;
      align-content: center;
      justify-content: center;
      padding-top: 20px;
      padding-bottom: 100px;
      background-image: url('./../assets/bg2.png');
      width: 100%;
    }



    .bg2 h1{
      color: white;
      text-align: center;
      font-size: 35px;
      font-family: 'Ubuntu', sans-serif;
    }
    .bottomImage{
      background-image: url('./../assets/endbg.png');
      width: 100%;
    }

    .mobile{
      align-items: center;
      align-content: center;
    }

    .ending {
      font-size: 15px;
      color: blue;
      text-align: center;
      font-family: 'Work Sans', sans-serif;
      color: rgb(34, 80, 129);
    }



    .centerimages{
      margin-left: 0px;
      margin-top: 50px;
    }

    .parasilver{
      margin-top: 30px;
      color: #7f828b;
      text-align: center;
    }
    .orangehead{
      text-align: center;
      margin-top: 200px;
      font-family: 'Ubuntu', sans-serif;
      font-size: 50px;
    }
    .orangehead2{
      text-align: center;
      margin-left: 0px;
      margin-top: 20px;
      font-size: 20px;
      color: rgba(113, 115, 126, 0.99);
    }


    .orange{
      color: #ff9e07;
    }

    .margindouble{
      padding-top: 180px;
    }

    .reactnativetext{
      margin-top: 350px;

    }
    .textmarginreactnative{
      margin-right: 30px;
      margin-top: 150px;
    }
    .unlimitedproductstext{
      margin-top: 100px;
      text-align: center;
      font-size: 40px;
      font-family: 'Ubuntu', sans-serif;
    }

    .paymentgateways{
      padding-bottom: 50px;
    }

    .package{
      background: #FFFFFF;
      border-top: 5px solid darkorange;
      border-radius: 8px;
      box-shadow: 0 5px 25px -13px rgb(0, 0, 0);
      width: 100%;
      height: 569px;
    }

    .package .package-content h4{
      text-align: center;
      padding-bottom: 50px;
      padding-top: 50px;
    }

    .package .package-content button{
      display: block;
      margin-left: auto;
      margin-right: auto;
      background-color: rgb(255, 144, 23);
      font-size: 15px;
      width: 120px;
      height: 40px;
      color: whitesmoke;
      border-radius: 20px;
    }

    .package .package-content {
      align-content: center;
      align-items: center;
    }


    .package .package-content ul{
      margin: 0;
      padding-bottom: 100px;
      padding-top: 30px;
      list-style: none;
      padding-left: 0px;
    }
    .package .package-content ul li{
      text-align: center;

    }
    .package .package-content p{
      text-align: center;
      color: darkorange;
      font-size: 70px;
      font-family: 'Ubuntu', sans-serif;;
    }
    .logotradebakerz{
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 25%;
      margin-top: 30px;
      padding-top: 50px;
      padding-bottom: 50px;
    }

    .contactus{
      margin-top: 70px;
      display: block;
      margin-right: auto;
      margin-left: auto;
      width: 550px;
    }


    .bgpink{
      background-image: url('./../assets/pinkbg.png');
      width: 100%;
      background-repeat: no-repeat;
    }
    .logofront{
      margin-top: 50px;
      width: 250px;
      margin-left: 50px;
    }
    .bgunlimitedproducts{
      padding-top: 100px;
      background-image: url('./../assets/circle2.png');
      background-repeat: no-repeat;
      background-position-x: 50px;
      width: 100%;
    }


    .formpad{
      margin-top: 80px;
      /*margin-right: 50px;*/
    }

    .bgscreenshots{
      background-image: url('./../assets/screenshotbackgroun.png');
      background-size: 1300px 600px;
      background-repeat: no-repeat;
      margin-top: 50px;
      background-position-x: 35px;
      background-position-y: 105px;
    }

    .bg3for3{
      background-image: url('./../assets/bg3for3.png');
      background-size: auto;
      background-repeat: no-repeat;
      margin-top: 50px;
    }


    .screenshots{
      text-align: center;
    }

    .bg3head{
      margin-top: 50px;
      text-align: center;
    }

    .googlefont{
      font-size: 50px;
      font-family: 'Ubuntu', sans-serif;
    }
    .unlimitedproductspara{
      margin-top: 30px;
      margin-left: 0px;
      font-size: 20px;
      color: #7d818d;
    }

    .textgooglenormal{
      font-family: 'Ubuntu normal', sans-serif;
      font-size: 40px;
    }

    .reactnativetemplateimage{
      background-image: url('./../assets/bg4.png');
      background-size: auto;
      background-position-y: 100px;
      background-repeat: no-repeat;
    }
    .contactheading{
      font-size: 50px;
      font-family: 'Ubuntu', sans-serif;
      color: #2e468c;
    }
    .customButton{
      background-color: rgb(34, 80, 129);
      width: 80%;
      height: 45px;
      border-radius: 20px;
      margin-top: 30px;
      text-align: center;
    }

    .roundinput{
      border-radius: 20px;

    }

    .bgintuitive{
      background-image: url('./../assets/circle2.png');
      background-size: auto;
      background-repeat: no-repeat;
      background-position-x: -300px;
    }

    .packgaes-head{
      text-align: center;
      margin-bottom: 100px;
    }
    .about-us {
      text-align: center;
      margin-top: 50px;
    }

    .about-us h1{
      color: orange;
      font-family: 'Ubuntu', sans-serif;
      padding-bottom: 50px;
    }

    .demoapps{
      background-color: rgb(244, 244, 244);
      box-shadow: 0px 1px 20px 0px rgba(0, 0, 0, 0.2);
      width: 260px;
      height: 90px;
      border-radius: 50px;
      margin-top: 30px;
    }

    .demoapps p{
      text-align: center;
      padding-top: 10px;
    }

    .googleandapple{
      padding-left: 10px;
      font-size: 20px;
      font-family: WorkSans;
      color: rgb(34, 80, 129);
      font-family: 'Ubuntu', sans-serif;
    }

  }
  @media (min-width:992px ) and (max-width: 1400px) {
    @import url('https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i');
    @import url('https://fonts.googleapis.com/css?family=Work+Sans:400,700');

    .head1{
      color: white;
      font-family: 'Ubuntu', sans-serif;
      padding-top: 250px;
      font-size: 45px;
      text-align: center;
    }

    .firstcell{
      padding-top: 50px;
    }

    .frontimage{
      background-image: url('./../assets/background.jpg');
      width: 100%;
    }

    .bg2 {

      display: flex;
      flex-direction: row;
      align-content: center;
      justify-content: center;
      padding-top: 20px;
      padding-bottom: 100px;
      background-image: url('./../assets/bg2.png');
      width: 100%;
    }

    .bg2 h1{
      color: white;
      text-align: center;
      font-size: 35px;
      font-family: 'Ubuntu', sans-serif;
    }
    .bottomImage{
      background-image: url('./../assets/endbg.png');
      width: 100%;
    }

    .mobile{
      display: block;
      margin-right: auto;
      margin-left: auto;
    }

    .ending {
      font-size: 15px;
      color: blue;
      text-align: center;
      font-family: 'Work Sans', sans-serif;
      color: rgb(34, 80, 129);
    }

    .centerimages{
      margin-right: 0px;
      padding-left: 50px;
      margin-top: 50px;
    }

    .parasilver{
      margin-top: 30px;
      color: #7f828b;
    }
    .orangehead{
      float: right;
      margin-top: 200px;
      font-family: 'Ubuntu', sans-serif;
      font-size: 50px;
    }
    .orangehead2{
      margin-left: 100px;
      float: right;
      margin-top: 20px;
      font-size: 20px;
      color: rgba(113, 115, 126, 0.99);
    }


    .orange{
      color: #ff9e07;
    }

    .margindouble{
      padding-top: 50px;
    }

    .reactnativetext{
      margin-top: 50px;
    }
    .textmarginreactnative{
      padding-top: 150px;
      margin-top: 50px;
      padding-bottom: 50px;
    }
    .unlimitedproductstext{
      margin-top: 100px;
      text-align: center;
      font-size: 45px;
      font-family: 'Ubuntu', sans-serif;
    }

    .paymentgateways{
      font-family: WorkSans;
    }
    .paymentgateways div{
      margin-top: 100px;
    }

    .paymentgateways p{
      color: darkslategray;
      font-size: 16px;
      float: right;
    }

    .package{
      background: #FFFFFF;
      border-top: 5px solid darkorange;
      border-radius: 8px;
      box-shadow: 0 5px 25px -13px rgb(0, 0, 0);
      width: 100%;
      height: 569px;
    }

    .package .package-content h4{
      text-align: center;
      padding-bottom: 50px;
      padding-top: 50px;
    }

    .package .package-content button{
      align-content: center;
      display: block;
      margin-right: auto;
      margin-left: auto;
      background-color: rgb(255, 144, 23);
      font-size: 20px;
      width: 120px;
      height: 45px;
      color: whitesmoke;
      border-radius: 20px;
    }

    .package .package-content {
      align-content: center;
      align-items: center;
    }


    .package .package-content ul{
      margin: 0;
      padding-bottom: 100px;
      padding-top: 30px;
      list-style: none;
    }
    .package .package-content ul li{
      text-align: center;

    }
    .package .package-content p{
      text-align: center;
      color: darkorange;
      font-size: 70px;
      font-family: 'Ubuntu', sans-serif;;
    }
    .logotradebakerz{
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 25%;
      margin-top: 30px;
      padding-top: 50px;
      padding-bottom: 50px;
    }

    .contactus{
      display: block;
      margin-right: auto;
      margin-left: auto;
      width: 750px;
    }


    .bgpink{
      background-image: url('./../assets/pinkbg.png');
      width: 100%;
      background-repeat: no-repeat;
    }
    .logofront{
      margin-top: 50px;
      width: 250px;
      margin-left: 50px;
    }
    .bgunlimitedproducts{
      background-image: url('./../assets/circle2.png');
      background-repeat: no-repeat;
      background-position-x: 50px;
      width: 100%;
    }


    .formpad{
      margin-top: 80px;
      margin-right: 0px;
    }


    .bgscreenshots{
      background-image: url('./../assets/screenshotbackgroun.png');
      background-size: 1300px 600px;
      background-repeat: no-repeat;
      margin-top: 50px;
      background-position-x: 35px;
      background-position-y: 105px;
    }

    .bg3for3{
      background-image: url('./../assets/bg3for3.png');
      background-repeat: no-repeat;
      background-size: auto;
      margin-top: 50px;
      margin-left: 0px;
      margin-right: 0px;
    }

    .screenshots{
      text-align: center;
    }

    .bg3head{
      margin-top: 50px;
    }

    .googlefont{
      font-size: 50px;
      font-family: 'Ubuntu', sans-serif;
    }

    .unlimitedproductspara{
      margin-top: 30px;
      text-align: center;
      font-size: 20px;
      color: #7d818d;
    }

    .textgooglenormal{
      font-family: 'Ubuntu normal', sans-serif;
      font-size: 40px;
    }

    .reactnativetemplateimage{
      background-image: url('./../assets/bg4.png');
      background-size: auto;
      background-position-y: 100px;
      background-repeat: no-repeat;
    }
    .contactheading{
      font-size: 45px;
      color: rgb(34, 80, 129);
      font-family: 'Ubuntu', sans-serif;
      text-transform: uppercase;
    }

    .customButton{
      background-color: rgb(34, 80, 129);
      width: 100%;
      height: 45px;
      border-radius: 20px;
      margin-top: 30px;
      text-align: center;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    .roundinput{
      border-radius: 20px;
    }

    .bgintuitive{
      background-image: url('./../assets/circle2.png');
      background-size: auto;
      background-repeat: no-repeat;
      background-position-x: -300px;
    }

    .packgaes-head{
      text-align: center;
      margin-bottom: 100px;
    }
    .about-us {
      text-align: center;
      margin-top: 50px;
    }

    .about-us h1{
      color: orange;
      font-family: 'Ubuntu', sans-serif;
      padding-bottom: 50px;
    }

    .demoapps{
      background-color: rgb(244, 244, 244);
      box-shadow: 0px 1px 20px 0px rgba(0, 0, 0, 0.2);
      width: 250px;
      height: 90px;
      border-radius: 50px;
      margin-top: 30px;
    }

    .demoapps p{
      text-align: center;
      padding-top: 10px;
    }

    .googleandapple{
      padding-left: 10px;
      font-size: 20px;
      font-family: WorkSans;
      color: rgb(34, 80, 129);
      font-family: 'Ubuntu', sans-serif;
    }
    .small{

      width: 350px;
      height: 70px
    }

    .reactnative-image img{
      margin-left: 0px;
      margin-right: 0px;
    }
  }

  @media only screen and (min-width: 768px) {
    .cd-top {
      right: 20px;
      bottom: 20px;
    }
  }

  @media only screen and (min-width: 1024px) {
    .cd-top {
      height: 60px;
      width: 60px;
      right: 30px;
      bottom: 30px;
    }
  }

</style>
