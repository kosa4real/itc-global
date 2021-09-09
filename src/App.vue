<template>
  <Header />
  <Carousel />
  <AboutUs />
  <Solutions/>
  <Contact />
<!--  <div id="nav">-->
<!--    <router-link to="/">Home</router-link> |-->
<!--    <router-link to="/about">About</router-link> |-->
<!--    -->
<!--  </div>-->
  <router-view/>
  <Footer />
</template>

<script>
  import Header from './components/Header'
  import Carousel from './components/Carousel'
  import AboutUs from './components/AboutUs'
  import Footer from './components/Footer'
  import Solutions from "./components/Solutions";
  import Contact from "./components/Contact";


  export default{
    name: "App",
    components:{
      Contact,
      Solutions,
      Header,  
      Footer,
      Carousel,
      AboutUs,
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

}

h5, h6 {
  font-family: "Biryani", Arial, Tahoma, sans-serif;
}

h6, h6 a, h6 a:hover, a.content_link .title {
  color: #f16C36;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
