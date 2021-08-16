<template>
  <nav class="navbar sticky-top navbar-expand-lg bg-dark">
    <div class="container_full">
      <div class="d-md-block d-flex">
        <a class="navbar-brand" href="#">
          <img src="@/assets/images/logo.png" alt="logo" />
        </a>
        <button
          class="navbar-toggler border-0 ml-auto hidden-sm-up float-xs-right"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto w-100 justify-content-end">
          <li class="nav-item active">
            <a class="nav-link active" href="#"> Home </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">NFT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">HIDD Token</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Roadmap</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Team</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Media</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Login</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button.navbar-toggler:focus {
  outline: none;
  border: none;
}
@media only screen and (max-width: 1440px) {
  a.navbar-brand img {
    width: 60%;
    margin-top: 11px;
  }
}
@media only screen and (max-width: 768px) {
  a.navbar-brand img {
    width: 60%;
    margin-top: 0px;
  }
  button.navbar-toggler {
    margin-top: 20px;
  }
}

@media only screen and (max-width: 425px) {
  button.navbar-toggler {
    margin-top: 0px;
  }
}
</style>
