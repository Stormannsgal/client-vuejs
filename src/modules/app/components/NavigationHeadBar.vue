<script setup>
</script>

<template>
  <nav class="navbar navbar-expand-sm navbar-dark">
    <div class="container-fluid">
      <router-link :to="{name: 'app_home'}" class="navbar-brand"><i class="bi bi-house-door-fill h2"></i></router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
              aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-sm-0">
          <li class="nav-item">
            <router-link :to="{name: 'app_home'}" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <router-link :to="{name: 'app_login'}" class="nav-link"><i class="bi bi-person-circle"></i> Anmelden</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
a:link, a:visited {
  text-decoration: none;
}

a:hover, a:active {
  text-decoration: none;
}
.navbar-dark {
  background-color: #192339;
}

.dropdown-menu {
  background-color: #202e4b;
}

.dropdown-menu > li > a:link, a:visited {
  color: lightgray;
}

.dropdown-menu > li > a:hover, a:active {
  color: white;
  background-color: #28395c;
}
</style>
