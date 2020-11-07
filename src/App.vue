<template>
  <div id="app">
    <HelloWorld msg=".."/>  
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
export default {
  name: "App",
  components: {
    HelloWorld,
  },

  data: function () {
    return {
  
    };
  },

  methods: {
    
  },
};
</script>

<style>

body{
  background-image: url(https://a-static.besthdwallpaper.com/battlefield-1-ekm-thamlaayhlangsngkhraam-wx-ll-pepexr-2560x1600-16519_7.jpg);
  background-size: 100%;
}
#app {
font-family: 'Metal Mania', cursive;  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 30px;
}

.cardtop{
  font-family: 'Bungee', cursive;
  font-size: 40px;
}
/*body{
  background-image: url(./assets/b1.gif);
  background-attachment:fixed;
}*/
</style>


