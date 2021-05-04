<template>
  <div>
    <div class="container-fluid">
      <div class="row">
        <nav class="navbar shadow bg-white col-12 mb-5">
          <a class="navbar-brand" href="#">Youcode Youssofia</a>
          <div>
            <router-link to="/login">
              <button type="button" class="btn btn-outline-primary mr-3">
                Login
              </button>
            </router-link>
            <router-link to="/signup">
              <button type="button" class="btn btn-outline-primary mr-3">
                Signup
              </button>
            </router-link>
          </div>
        </nav>
      </div>
    </div>
    <div class="container-fuild">
      <div
        class="row w-100 d-flex justify-content-center align-items-center"
        style="height:85vh;"
      >
        <div class="col-12">
          <router-view />
        </div>
      </div>
    </div>
  </div>
</template>

<style>
body {
  background: rgba(37, 85, 254, 255);
}
</style>
