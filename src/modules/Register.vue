<template>
  <div>
    <center>
      <h1 class="text-primary">Register</h1>
    </center>
    <div class="row loginPage">
      <div class="col-md-4"></div>
      <div class="col-md-4">
        <div class="container">
          <div class="card">
            <div class="card-header">Login</div>
            <div class="card-body">
              <div class="form-group">
                <label for="fullname" class="bmd-label-floating">Fullname</label>
                <input
                  type="text"
                  class="form-control"
                  id="fname"
                  placeholder="Enter your fullname here!"
                />
              </div>
              <div class="form-group">
                <label for="Username" class="bmd-label-floating">Username</label>
                <input
                  type="text"
                  class="form-control"
                  id="uname"
                  placeholder="Enter your username!"
                />
              </div>
              <div class="form-group">
                <label for="password" class="bmd-label-floating">Password</label>
                <input
                  type="password"
                  class="form-control"
                  id="passw"
                  placeholder="Enter your password!"
                />
              </div>
              <div class="form-group">
                <label for="cpassword" class="bmd-label-floating">Confirm Password</label>
                <input
                  type="password"
                  class="form-control"
                  id="cpassw"
                  placeholder="Enter your password!"
                />
              </div>
                <button type="button" class="btn btn-outline-success login-btn" id="btnLogin">Login</button>
                <!-- <input type = "login" class = "form -control" id = "login" value = "Login" v-on:> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
 <script>
 </script>
<style scoped>
</style>
