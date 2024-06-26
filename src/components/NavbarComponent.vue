<template>
    <div class="navbar-conatiner">
        <div class="container">
            <div class="row pt-5">
                <div class="col-lg-2">
                    <div class="w-100">
                        <img class="w-100" :src="logoo" />
                    </div>
                </div>
                <div class="col-lg-10">
                    <nav class="navbar navbar-expand-lg navbar-light px-3">
            <div class="container-fluid p-0">
              <button
                class="navbar-toggler"
                type="button"
                data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="navbarDropdown"
                      role="button"
                      aria-expanded="false"
                    >
                      Home
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider" /></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="navbarDropdown"
                      role="button"
                      aria-expanded="false"
                    >
                      About
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider" /></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="navbarDropdown"
                      role="button"
                      aria-expanded="false"
                    >
                      Products
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider" /></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="Core"
                      role="button"
                      aria-expanded="false"
                    >
                      Core Products
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="Core">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider" /></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                 
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="principals"
                      role="button"
                      aria-expanded="false"
                    >
                      principals
                    </a>
                  
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="navbarDropdown"
                      role="button"
                      aria-expanded="false"
                    >
                      Events
                    </a>
              
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="award"
                      role="button"
                      aria-expanded="false"
                    >
                      Awards and Affiliations
                    </a>
              
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="CSR"
                      role="button"
                      aria-expanded="false"
                    >
                      CSR
                    </a>
                  
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link  navbar-content-item"
                      href="#"
                      id="contact"
                      role="button"
                      aria-expanded="false"
                    >
                      Products
                    </a>
                   
                  </li>

                </ul>
              </div>
            </div>
          </nav>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
import logo from '@/assets/logo.png'; // Adjust the path based on your project structure

export default {
    name:"NavbarComponent",
    data() {
        return {
            logoo: logo // Assign the imported image to the logo data property
        };
    }
};
</script>
<style scoped lang="scss">
.navbar-nav .nav-item.dropdown:hover .dropdown-menu {
  display: block;
}

.navbar-nav .nav-item.dropdown:hover .nav-link {
  background-color: #f8f9fa; /* Optional: highlight the dropdown on hover */
}
</style>