<template>
  <footer class="pt-5 pb-2">
    <div class="container">
      <div class="row mt-3">
        <div class="col-md-4">
          <img src="../assets/itc-logo.png" alt="" width="200">
        </div>
        <div class="col-md-4 text-start">
          <p>
            <b>Company</b>
          </p>
            <p class="mb-3"><router-link to="#about" class="router-link">About US</router-link></p>
            <p class="mb-3"><router-link to="#solutions" class="router-link">Our Solutions</router-link></p>
            <p class="mb-3"><router-link to="#contactus" class="router-link">Contact Us</router-link></p>

        </div>
        <div class="col-md-4 text-start">
          <p>
            <b>Information</b>
          </p>
          <p>Plot MDR125A Yusuf Kurfi Street, Railway Quaters - Kano State.</p>
          <p>info@itcglobal.ng</p>
          <p>0704 969 1922</p>
        </div>
      </div>
    </div>
    <hr>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <p class="text-center">Copy right 2020. All right reserved</p>
        </div>
      </div>
    </div>
  </footer>


</template>

<script>
export default {
  name: 'Footer'
}

</script>

<style scoped>
footer{
  background-color: #03304a;
  color:#8aa0ad;
}
.router-link{
  text-decoration: none;
}

</style>