<template>
  <nav class="navbar navbar-expand-lg bg-light navbar-dark py-3 scroll-top">
      <div class="container">
        <router-link class="navbar-brand" to="#">
          <img class="logo" src="../assets/itc-logo.png" alt="">
        </router-link>

      <!-- Mobile Button -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu" >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse " id="navmenu">
        <ul class="navbar-nav ms-auto text-seondary">
          <li class="nav-item"><a class="nav-link active" aria-current="page" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" aria-current="page" href="#aboutus">About-us</a></li>
          <li class="nav-item"><a class="nav-link" aria-current="page" href="#solutions">Our Solutiona</a></li>
          <li class="nav-item"><a class="nav-link" aria-current="page" href="#contactus">Contact Us</a></li>
        </ul>
      </div>
      </div>
    </nav>
</template>

<script>
  export default{
    name: 'Header',

  }
</script>

<style>
.logo{
  width: 200px;
  height: 50px;
}
.navbar-dark .navbar-nav .nav-link {
  color:#f16C36;
}
.navbar-dark .navbar-nav .nav-link.active {
  color:#f16C36;
}
.navbar-dark .navbar-nav .nav-link:hover {
  color:#f16C36;
  font-weight: bold;
}
<style>

@media screen {
  
}

</style>